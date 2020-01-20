---
layout: post
title: Whitespace and Line Breaks
author: typora.io
category: how-to
tags: [style, markdown]
typora-root-url: ../
---

## Recommended Practices in Typora

Line breaks can be very confusing in Markdown. Our recommendations is that you:

- use Typora's default setting
- write in Typora's hybrid view
- press `Enter` or `Return` key to insert new paragraphs and avoid insert new lines
- If you do need to add a single hard line break, use the syntax: `<br/>`

## Single Line Breaks

The single line break is parsed differently across different Markdown engines, and **CommonMark** will just ignore it. So if you write:

```markdown
line 1
line 2
```

it will be rendered as

>  line 1 line 2

But other markdown engines may choose to keep the line break (like input box for issues in GitHub), or provide options whether to preserve it or not.

In **Typora**, we provide options in the Preference Panel > Markdown > Whitespace / Line Break whether to preserve it or not. By default, Typora will **Preserve line breaks in editing view and ignore them when printing or exporting.**

## Whitespace

Sequential whitespace is similar to Single Line Breaks, and most Markdown engines will ignore them. For example, in `CommonMark`

```markdown
Four    whitespace in between
```

will be converted to HTML

```html
<p>Four    whitespace in between</p>
```

but you will only see

Four whitespace in between

By default, Typora will **Preserve sequential whitespace in editing view and ignore them when printing or exporting.** You can change this option in preference panel.

If you do want to insert sequential whitespace that other markdown engines support, you can:

- escape whitespace, type `\` before every whitespace
- use HTML entity `&nbps;`.

## `Enter` key in Typora

In Markdown, **two consecutive line breaks** means create a new paragraph. In Typora, when you press `Enter` key, a new paragraph is created, and if you switch to source code mode, two line breaks are inserted. For example, source of

> Paragraph 1
>
> Paragraph 2

creates

```markdown
paragraph 1
(empty line)
paragraph 2
```

You can explicitly insert a single line break in editing view by pressing `Shift`+`Enter` key.

## Markdown Line Break

Markdown provides ways to insert a single hard line break:

- insert two whitespace and a line break
- insert HTML tag `<br/>` directly

Almost all Markdown engines will parse them as hard line break in the output.

## Change Related Settings in Typora

We provide related settings in `Preference Panel` or `Edit` -> `Whitespace and  Line Breaks` from the menu bar.
