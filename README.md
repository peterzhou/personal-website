# Personal Website

This is Peter Zhou's personal website and blog, built with Hugo and deployed via GitHub Pages.

## Local Development

```bash
# Run local development server
hugo server -D

# Build static site
hugo
```

## Adding New Posts

Create a new post:
```bash
hugo new content posts/my-new-post.md
```

Then edit the file in `content/posts/` and set `draft: false` when ready to publish.

## Deployment

The site automatically deploys to GitHub Pages when changes are pushed to the `main` branch.

The site will be available at: https://peterzhou.github.io/personal-website/

## Theme

Using [PaperMod](https://github.com/adityatelange/hugo-PaperMod) theme.
