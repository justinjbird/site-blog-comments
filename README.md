# Blog Comments

## What is this?

This repository stores comments from blogs posts at <https://justinjbird.me>

## How is that set up?

Site powered by [Hugo](https://gohugo.io), comments are powered by [giscus](https://giscus.app/)

## How does that work?

Comments on a page result in a discussion thread in this repository, can read more about that [here](https://www.justinjbird.me/2023/giscus-for-hugo/)

## What else is here

### Todoist notifications

I have created a [workflow](./.github/workflows/discussion-to-todoist.yml) to notify me via todoist if someone writes a comment on my blog.

### Giscus themes

Custom light/dark CSS for the blog comment widget:

- `./giscus/palette.css` — site colour tokens (edit here)
- `./giscus/light.css` / `./giscus/dark.css` — Giscus theme mappings

These are loaded as the light and dark themes for my giscus comments.
