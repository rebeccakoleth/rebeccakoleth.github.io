# a small corner — jekyll blog theme

pastel greens, blues, and pinks. playfair display + lora. yours to fill.

## setup

### 1. create a github repo
go to github.com → new repository → name it `yourusername.github.io`
(or any name if you want a project site)

### 2. upload these files
drag and drop everything in this folder into your new repo,
or use git:
```
git init
git add .
git commit -m "first commit"
git remote add origin https://github.com/yourusername/yourusername.github.io
git push -u origin main
```

### 3. enable github pages
repo settings → pages → source: main branch → save
your site will be live at `https://yourusername.github.io` in a minute or two.

---

## writing a new post

create a file in `_posts/` named like:
```
2026-04-01-whatever-you-want-to-call-it.md
```

start it with:
```
---
layout: post
title: "your title here"
date: 2026-04-01
tags: [optional, tags]
---

your writing goes here.
```

that's it. push to github and it appears.

---

## customizing

**colors** → `assets/css/main.scss` at the top, the `:root` variables
**site title & description** → `_config.yml`
**about page** → `about.html`
**home intro** → `index.html`
**add buttons/links** → edit the nav in `_layouts/default.html`

---

## adding a custom nav button

in `_layouts/default.html`, find the nav-links list and add:
```html
<li><a href="/yourpage">your page</a></li>
```

then create `yourpage.html` with `layout: default` at the top.

---

made with care. make it yours.
