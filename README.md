# Blog

Personal blog, built with [Hugo](https://gohugo.io/) and deployed to GitHub Pages
by `.github/workflows/hugo.yml` on every push to `main`.

## Writing a post

Add a Markdown file to `content/posts/`:

```markdown
---
title: "My post"
slug: "my-post"
date: 2026-10-14
---

Post body here.
```

It will be published at `/blog/2026/10/14/my-post.html`.

## Running locally

```sh
hugo server
```

Then open <http://localhost:1313/blog/>.
