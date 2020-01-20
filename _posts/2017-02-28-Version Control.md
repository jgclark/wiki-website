---
layout: post
title: Version Control and Recovery
author: typora.io
category: how-to
tags: [auto-save, history, version]
typora-root-url: ../
typora-copy-images-to: ../media/version-control
---

## macOS

On macOS, Typora integrates with the native version control function provided by the operating system.

You can simply choose `File` > `Revert To` > `Browse All Versions` from the menu to browse and revert to a particular version. More details can be found [here](https://support.apple.com/kb/PH25757?viewlocale=en_US&locale=en_US).

![Snip20170228_6](/media/version-control/Snip20170228_6.png)

For **untitled** drafts, they are located in `~/Library/Autosave Information`. But please save them just in case.

## Windows/Linux 

Windows 10 also has [version control built into the operating system](http://www.pcworld.com/article/2974385/windows/how-to-use-windows-10s-file-history-backup-feature.html)).

Typora on Window/Linux does not provide version control, but can save drafts regularly to prevent data lost, when Typora exits or crashes without saving file, or you accidentally quit Typora without saving your writings.

You can open preference panel, under "Editor" section, click the "Recover Unsaved Drafts" button to found some writing drafts auto saved by Typora.

![Snip20170228_7](/media/version-control/Snip20170228_7.png)

The filenames of those backed-up drafts is like `{date}-{filename}.md`.  If your content is newly created without a file path (which is, "Untitled"), the `{filename}` part is auto generated, which is usually the first heading or first sentence. You can find and copy out the corresponding backup file to retrieve your work.

Also, Typora for Window/Linux has an [autosave](/Auto-Save/) feature.
