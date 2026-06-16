# saverionapolitano.github.io

Personal site of **Saverio Napolitano** — AI Engineering MSc student (Unimore),
built with [Jekyll](https://jekyllrb.com/) and hosted on GitHub Pages.

## Structure

```
_config.yml        Site config, nav, plugins
_layouts/          default · page · post
assets/main.scss   All styling (compiled to /assets/main.css)
index.md           Home (hero, about, experience, skills, projects, contact)
blog.md            Post listing (/blog/)
_posts/            Blog posts
```

## Local development

```bash
bundle install
bundle exec jekyll serve   # http://localhost:4000
```

## Adding a blog post

Create `_posts/YYYY-MM-DD-title.md`:

```markdown
---
layout: post
title: "My post"
date: 2026-01-09
tags: [ai, notes]
---

Content here.
```

## License

[MIT](LICENSE)
