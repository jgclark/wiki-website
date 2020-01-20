---
layout: post
title: Change Width of Writing Area
author: typora.io
category: how-to
tags: [style]
typora-root-url: ../
---

> NOTE: Some of the following CSS style will only work for latest version of Typora (>= 0.9.9.6 on macOS, and >=0.9.13 on Windows).

> TIP: To learn more about where to put CSS snippets, please see [Add Custom CSS](/Add-Custom-CSS/).

You can set the writing area width directly. For example:

```css
#write {
  max-width: 1800px; /*adjust writing area position*/
}
```
You can also use other CSS styles like `padding-left` or `padding-right` to adjust the padding around the writing area instead. For example:

```css
#typora-source .CodeMirror-lines {
  max-width: auto; /*or 1000px*/
}
```
