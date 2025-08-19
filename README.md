# JarEngine™

A personal blog built with [Astro](https://astro.build) using the Cactus theme.

## Features

- ⚡ Fast static site generation with Astro
- 🎨 Beautiful, responsive design with Tailwind CSS
- 🌙 Dark/Light mode toggle
- 📱 Mobile-friendly responsive layout
- 🔍 Built-in search functionality
- 📝 Blog posts with markdown/MDX support
- 📄 Notes for shorter content
- 🏷️ Tag-based content organization
- 🖼️ Automatic OG image generation
- 📊 SEO optimized

## Getting Started

### Prerequisites

- Node.js (version 18 or higher)
- pnpm (recommended) or npm

### Installation

1. Clone this repository
2. Install dependencies:

```bash
pnpm install
```

3. Start the development server:

```bash
pnpm dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser

## Configuration

Edit `src/site.config.ts` to customize:

- Site title and description
- Author information
- Social links
- URL and domain settings

## Content

### Adding Blog Posts

Create new `.md` or `.mdx` files in `src/content/post/` with frontmatter:

```yaml
---
title: "Your Post Title"
description: "Post description for SEO"
publishDate: "2024-01-01"
tags: ["tag1", "tag2"]
---
```

### Adding Notes

Create new `.md` files in `src/content/note/` for shorter content:

```yaml
---
title: "Note Title"
publishDate: "2024-01-01"
---
```

## Commands

| Command | Action |
| :--- | :--- |
| `pnpm install` | Install dependencies |
| `pnpm dev` | Start local dev server |
| `pnpm build` | Build for production |
| `pnpm preview` | Preview production build |
| `pnpm postbuild` | Build search index |

## Deployment

This site is configured for **automatic deployment to GitHub Pages**. See [DEPLOYMENT.md](./DEPLOYMENT.md) for detailed setup instructions.

### Quick GitHub Pages Setup:
1. Push this repo to GitHub
2. Go to Settings → Pages → Source → Select "GitHub Actions"
3. Update your username in `src/site.config.ts`
4. Push to main branch - your site will auto-deploy!

The site can also be deployed to other static hosting services like:
- [Netlify](https://netlify.com)
- [Vercel](https://vercel.com)
- [Cloudflare Pages](https://pages.cloudflare.com)

## License

MIT License - feel free to use this code for your own projects.

## Credits

Built with the [Astro Cactus](https://github.com/chrismwilliams/astro-theme-cactus) theme.