# Landing site

This folder is ready for static hosting (Cloudflare Pages, Netlify, Vercel static mode).

## Current structure

- `index.html` - main landing page
- `blog/index.html` - blog list page
- `blog/template-post.html` - reusable template for new blog posts
- `.gitignore` - ignores local system files

## How to add a new blog post

1. Copy `blog/template-post.html`
2. Rename copy, for example: `blog/how-to-start-ai-project.html`
3. Change title, date, and content in that file
4. Add a link to the new article in `blog/index.html`

## Deploy notes

- No build step is required.
- Root directory for deploy is this folder.
- Entry point is `index.html`.
