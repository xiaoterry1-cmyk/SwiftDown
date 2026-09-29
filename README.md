<p align="center">
  <img src="assets/icon.png" alt="SwiftDown app icon" width="128" height="128">
</p>

<h1 align="center">SwiftDown</h1>

<p align="center">
  A native Markdown editor for macOS with WYSIWYG inline editing, live preview, code highlighting, math, and Mermaid diagrams. Everything works offline.
</p>

<p align="center">
  <a href="../../issues/new?template=bug_report.yml">Report a bug</a> ·
  <a href="../../issues/new?template=feature_request.yml">Suggest an idea</a> ·
  <a href="../../issues">Browse existing issues</a>
</p>

---

## About this repository

This repository is the public issue and feedback tracker for SwiftDown. Use it to report bugs, suggest ideas, and discuss product improvements.

The SwiftDown source code is not hosted here.

## Before you open an issue

1. [Search existing issues](../../issues?q=is%3Aissue) first. If someone has already reported the same thing, add a 👍 reaction or extra details instead of opening a duplicate.
2. Make sure you are running the latest version of SwiftDown. Your issue may already be fixed.
3. Keep it to one bug or one idea per issue so it can be tracked and closed cleanly.

## Reporting a bug

Use the [bug report form](../../issues/new?template=bug_report.yml). The more of this you include, the faster we can track it down:

- SwiftDown version (SwiftDown → About SwiftDown)
- macOS version and Mac type (Apple silicon or Intel)
- The view mode you were in: Inline (⌘1), Source (⌘2), Split (⌘3), or Preview (⌘4)
- Steps to reproduce, what you expected, and what actually happened
- A minimal Markdown snippet that reproduces the problem (remove anything sensitive)
- Screenshots or a screen recording, and a crash report if the app crashed

For rendering issues (tables, math, Mermaid, images, code highlighting), the raw Markdown source matters most. For large-file or encoding issues, mention the file size and encoding.

## Suggesting an idea

Use the [feature request form](../../issues/new?template=feature_request.yml) and tell us:

- The problem you're trying to solve or the workflow you're in
- What you'd like SwiftDown to do
- How you work around it today, if at all

"When I do Y, I keep needing Z" helps us more than "add an X button".

## Features at a glance

| Feature | Details |
| --- | --- |
| Four view modes | Source, Split (synced scrolling), Preview, and Inline WYSIWYG. Each file remembers its last mode |
| Formatting | Floating toolbar on selection, a window toolbar, and keyboard shortcuts |
| Heading folding | Fold sections in Inline mode; promote or demote with ⌃⌘↑ / ⌃⌘↓ |
| Table editing | Edit cells in place and add rows and columns in Inline mode |
| Code blocks | Syntax highlighting for fenced code blocks |
| Math | Inline `$...$` and block `$$...$$` formulas |
| Mermaid | Diagrams render in both the editor and preview |
| Images | Local images with relative paths and images from the web |
| Encodings | Automatic encoding detection; saving keeps the original encoding and line endings |
| Large files | Multi-megabyte documents open smoothly, with parsing in the background |
| Export | Export to PDF (⇧⌘E) |
| Offline | Everything needed for preview, highlighting, math, and diagrams ships inside the app |

## Labels

| Label | Meaning |
| --- | --- |
| `bug` | Something isn't working as expected |
| `enhancement` | A new feature or improvement |
| `question` | A usage question |
| `duplicate` | Already reported in another issue |
| `wontfix` | Not planned |

## Getting help

- For usage questions, open the Welcome document from the Help menu, or [start a discussion](../../discussions).
- For everything else, [open an issue](../../issues/new/choose).

## Privacy

SwiftDown processes your documents locally, and all rendering resources are bundled with the app. It only makes network requests to load images your document links to on the web. When filing an issue, please don't attach documents that contain personal or confidential information.

## Code of Conduct

Please be kind and respectful. This project follows the [Contributor Covenant](https://www.contributor-covenant.org/version/2/1/code_of_conduct/).
