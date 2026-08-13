# Abel Creates (abelcreates.com)

Personal website, portfolio, and blog built with [Jekyll](https://jekyllrb.com) and [Ruby](https://www.ruby-lang.org/), automatically deployed to **GitHub Pages** via **GitHub Actions**.

---

## 🚀 Quick Start (Local Development)

### 1. Prerequisites
Ensure you have Ruby 3.3+ and Bundler installed. If using `rbenv`:
```bash
rbenv install 3.3.8 # (if not already installed)
```

### 2. Install Dependencies
```bash
bundle install
```

### 3. Start Local Development Server
```bash
bundle exec jekyll serve --livereload
```
Open [http://127.0.0.1:4000](http://127.0.0.1:4000) in your browser.

---

## ✍️ Writing New Posts

Add new markdown files in `_posts/` with the filename format `YYYY-MM-DD-post-title.md`:

```markdown
---
layout: post
title: "My New Article"
date: 2026-08-13 14:00:00 -0400
description: "Brief summary of the article."
categories: [Engineering, Cloud]
tags: [ruby, jekyll]
---

Your post content here in Markdown...
```
