# Programming Blog

A personal blog focused on programming knowledge, built with Astro.

## Features

- 📝 MDX for writing blog posts
- 🔍 Full-text search functionality
- 📱 Mobile-responsive design
- 🔗 Social media sharing
- 📧 Newsletter subscription
- 📊 Google Analytics integration
- 🔄 RSS feed
- 🗺️ Sitemap for SEO
- 🌙 Dark mode support

## Getting Started

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd programming-blog
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Update Configuration:
   - Set your site URL in `astro.config.mjs`
   - Update Google Analytics ID in `Layout.astro`
   - Configure social media links in `Footer.astro`

4. Start the development server:
   ```bash
   npm run dev
   ```

5. Create blog posts:
   - Add `.mdx` files to `src/content/blog/`
   - Include required frontmatter (title, description, pubDate, image, tags)

## Deployment

This project is configured for deployment on Netlify:

1. Push your code to GitHub
2. Connect your repository to Netlify
3. Configure build settings:
   - Build command: `npm run build`
   - Publish directory: `dist`

## Writing Blog Posts

Create new `.mdx` files in `src/content/blog/` with the following frontmatter:

```mdx
---
title: "Your Post Title"
description: "A brief description of your post"
pubDate: "2024-02-20"
image: "/path/to/image.jpg"
tags: ["javascript", "react", "tutorial"]
---

Your content here...
```

## License

MIT License