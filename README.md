# AnimeNews

A modern anime blog built with **Astro** and designed for **Cloudflare Pages**.

## Features

- Beautiful dark anime-inspired theme (pink / purple / cyan accents)
- Fast static site generation
- Markdown blog posts with tags & categories
- Responsive design
- SEO ready (sitemap included)

## Getting Started

```bash
npm install
npm run dev
```

## Deploy to Cloudflare Pages

1. Connect this repository to Cloudflare Pages
2. Use these build settings:
   - **Framework preset**: Astro
   - **Build command**: `npm run build`
   - **Build output directory**: `dist`

## Writing Posts

Create new Markdown files in `src/content/blog/`:

```markdown
---
title: "Your Post Title"
description: "Short description"
pubDate: 2026-09-16
heroImage: "https://..."
tags: ["news", "review"]
category: "Reviews"
---

Your content here...
```

## License

MIT
