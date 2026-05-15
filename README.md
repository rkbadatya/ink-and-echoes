# Blogg

A personal blog built with [Hugo](https://gohugo.io/) and the [PaperMod](https://github.com/adityatelange/hugo-PaperMod) theme.

## Local Development

```bash
# Install Hugo (https://gohugo.io/installation/)
brew install hugo

# Start dev server (includes drafts)
hugo server --buildDrafts

# Build for production
hugo build
```

## Writing a New Post

```bash
hugo new content posts/my-new-post.md
```

Edit the generated file in `content/posts/`. Set `draft: false` when ready to publish.

## Deployment

Deployed to **Cloudflare Pages** with automatic builds on push.

- Build command: `hugo`
- Output directory: `public`
- Environment variable: `HUGO_VERSION` = `0.147.1`
