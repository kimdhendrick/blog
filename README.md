# blog

A minimal [Astro](https://astro.build) blog.

## Commands

```sh
npm install
npm run dev      # start local dev server
npm run build    # build to ./dist
npm run preview  # preview the production build
```

## Adding a post

Add a new Markdown file to `src/content/blog/` with frontmatter:

```md
---
title: 'My New Post'
description: 'A short description.'
pubDate: 2026-08-01
---

Post content goes here.
```

It'll automatically appear on `/blog`.
