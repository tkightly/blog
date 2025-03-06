---
title: "Themeing Jekyll"
date: 2025-03-06
---

It was a right pain. The docs say you can overwrite custom variables at `_sass/minima/custom-variables.scss` but nothing that I did updated them.

In the end, I forked the [Minima repo](https://github.com/jekyll/minima) and updated the `custom-variables.scss` file directly there, and pointed my Jekyll at the fork

I wonder if it's Github pages simply not pulling in the file the way the Minima docs say it should

But then the [Github Pages](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/adding-a-theme-to-your-github-pages-site-using-jekyll#customizing-your-themes-css) docs say to update the `/assets/css/style.scss`, which is probably a theme-agnostic way of doing it (although you probably would have to update the styles directly instead of simply editing the variables 🤔)
