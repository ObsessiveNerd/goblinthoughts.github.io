# Goblin Thoughts

A static home for game devlogs, film work, TTRPG notes, and general blogging.

## Add a post

Create a Markdown file anywhere inside `src/content/writing/`. Its frontmatter must include a title, description, publication date, and section:

```md
---
title: Devlog #2: The interesting bit
description: A short summary shown on listing pages.
pubDate: 2026-10-01
section: games # blog, games, film, or ttrpg
project: My Game # optional
tags: [devlog]
draft: false # optional; drafts never publish
---

Post content goes here.
```

For project-specific URLs, organize files in folders: `src/content/writing/games/my-game/devlog-02.md` becomes `/games/my-game/devlog-02/`.

## Local development

`npm.cmd run dev` starts the site. `npm.cmd run build` produces the GitHub Pages build.
