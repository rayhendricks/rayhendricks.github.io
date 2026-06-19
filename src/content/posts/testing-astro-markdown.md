---
title: "Testing Astro: A Markdown Playground"
author: Ray Hendricks
pubDatetime: 2026-06-19T12:00:00Z
slug: testing-astro-markdown
featured: true
draft: false
tags:
  - meta
  - test
description: The first post on this blog — a quick tour of what Astro and Markdown can render.
---

This is a test post. No real content here yet — it just exercises the things Markdown (and this theme) can do, so I can see what renders.

## Table of contents

## Text formatting

You get the usual basics: **bold**, _italic_, **_bold italic_**, ~~strikethrough~~, and `inline code`. Here is a [link to Astro](https://astro.build/), and a footnote reference.[^1]

[^1]: Footnotes render down here at the bottom of the post.

## Headings

### A third-level heading

#### A fourth-level heading

## Lists

Unordered:

- First item
- Second item
  - A nested item
  - Another nested item
- Third item

Ordered:

1. Step one
2. Step two
3. Step three

A task list:

- [x] Set up the blog
- [x] Pick a theme
- [ ] Write something real

## Blockquote

> The best way to predict the future is to invent it.
>
> — Alan Kay

## Callout

> [!NOTE]
> This is an Obsidian-style callout, supported by this theme. Handy for tips and warnings.

## Code block

```js
// Syntax highlighting via Shiki
function greet(name) {
  return `Hello, ${name}!`;
}

console.log(greet("world"));
```

## Table

| Feature        | Supported? |
| -------------- | :--------: |
| Dark mode      |     ✅     |
| Search         |     ✅     |
| RSS feed       |     ✅     |
| Syntax highlight |   ✅     |

## Horizontal rule

---

That's the tour. If everything above looks right on the live site, the pipeline works end to end.
