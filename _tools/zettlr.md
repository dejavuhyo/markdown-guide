---
title: Zettlr
category: documents
description: "Zettlr is an open source Markdown editor designed for academic writing."
icon: zettlr.png
website: https://www.zettlr.com/
syntax:
  - id: headings
    available: y
  - id: paragraphs
    available: y
  - id: line-breaks
    available: y
    notes: "In addition to trailing whitespace, you can also use a trailing backslash or press the Return key once to achieve the same result."
  - id: bold
    available: y
  - id: italic
    available: y
  - id: blockquotes
    available: y
  - id: ordered-lists
    available: y
  - id: unordered-lists
    available: y
  - id: code
    available: y
  - id: horizontal-rules
    available: y
  - id: links
    available: y
  - id: images
    available: y
  - id: tables
    available: y
  - id: fenced-code-blocks
    available: y
  - id: syntax-highlighting
    available: y
  - id: footnotes
    available: y
  - id: heading-ids
    available: y
  - id: definition-lists
    available: p
    notes: "No editor highlighting. Handled by pandoc on export."
  - id: strikethrough
    available: y
  - id: task-lists
    available: y
  - id: emoji-cp
    available: y
  - id: emoji-sc
    available: y
  - id: highlight
    available: y
    notes: "==text== or ::text:: syntax. Also [text]{.mark} via Pandoc span."
  - id: subscript
    available: y
  - id: superscript
    available: y
  - id: auto-url-linking
    available: y
  - id: disabling-auto-url
    available: n
  - id: html
    available: y
    notes: "HTML blocks and inline HTML supported. Handled by Pandoc on export."
---

[Zettlr](https://www.zettlr.com/) is free and open source Markdown application designed for academic writing. It provides a lot of powerful tools to help you write academic texts right out of the box.

The application's stated goal is simple: "Enabling researchers of arts and humanities, e.g. those people without any knowledge of coding, to finally free themselves from software that costs hundreds of dollars and pave the way into an Open Source era. This would be only fitting, given the fact that especially in political science and sociology, cries for Open Access journals are on the rise. So here’s what Zettlr is all about: It wants to be serious competition for word processors."

{% include image.html file="/assets/images/tools/zettlr_view.png" alt="Zettlr editor interface" %}

See the [Zettlr Documentation](https://docs.zettlr.com/en/) for the official documentation. Zettlr uses [Pandoc Markdown](https://pandoc.org/MANUAL.html#pandocs-markdown) as its dialect. Beyond syntax highlighting for CommonMark, GFM, and Pandoc extensions, Zettlr adds first-class support for Zettelkasten links and tags, citations with reference manager integration, footnotes, LaTeX math, and Mermaid diagrams. Excelling at academic workflows: project-based export to PDF, Word, HTML and others via Pandoc; custom templates for journals and conferences; a graph view for visualizing note connections. Additional features include multi-cursor editing, Emacs and Vim modes, snippets, spell and grammar checking (including LanguageTool), as well as a built-in Pomodoro timer.

{% include tool-syntax-table.html %}
