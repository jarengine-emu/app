# GitHub Pages Deployment Guide

This blog is configured for automatic deployment to GitHub Pages. Follow these steps to deploy your site:

## Prerequisites

1. Push this repository to GitHub
2. Make sure the repository is named `JarEngine` (or update the base path in `astro.config.ts`)

## Setup GitHub Pages

1. Go to your repository on GitHub
2. Click on **Settings** tab
3. Scroll down to **Pages** section in the left sidebar
4. Under **Source**, select **GitHub Actions**

## Configure Your Site

1. **Update your username**: 
   - Edit `src/site.config.ts`
   - Replace `yourusername` in the URL with your actual GitHub username
   - Example: `https://jarengine-emu.github.io/JarEngine/`

2. **Update repository name** (if different):
   - If your repository isn't named `JarEngine`, update the base path in `astro.config.ts`
   - Change `/JarEngine` to `/your-repo-name`

## Deployment Process

1. **Push to main branch**: 
   ```bash
   git add .
   git commit -m "Initial deployment setup"
   git push origin main
   ```

2. **Automatic deployment**:
   - GitHub Actions will automatically build and deploy your site
   - Check the **Actions** tab to see the deployment progress
   - Your site will be available at: `https://jarengine-emu.github.io/JarEngine/`

## Custom Domain (Optional)

If you want to use a custom domain:

1. **Update the site URL**:
   - Edit `src/site.config.ts`
   - Change `url` to your custom domain: `https://yourdomain.com/`

2. **Remove the base path**:
   - Edit `astro.config.ts`
   - Change the base configuration to: `base: '/',`

3. **Configure GitHub Pages**:
   - In repository Settings → Pages
   - Add your custom domain in the "Custom domain" field
   - Add a CNAME record in your DNS settings pointing to `yourusername.github.io`

## Troubleshooting

- **404 errors**: Make sure the base path in `astro.config.ts` matches your repository name
- **Deployment fails**: Check the Actions tab for error logs
- **Assets not loading**: Verify the site URL in `src/site.config.ts` is correct

## Local Development

For local development, the base path is automatically set to `/` so you can run:

```bash
npm install
npm run dev
```

And access your site at `http://localhost:4321/`
