---
layout: post
title: "Welcome to Abel Creates"
date: 2026-08-12 18:00:00 -0400
description: "Why I decided to rebuild my personal site using Jekyll, Ruby, and GitHub Pages."
categories: [General, Web]
tags: [jekyll, ruby, github-pages]
---

Welcome to my corner of the web! 🚀

I've set up **abelcreates.com** as a space to document what I'm working on, share technical writeups, and publish notes on software engineering, creative coding, and system design.

### Why Jekyll & Ruby?

When building a personal site, simplicity and durability win every time. Jekyll gives us:

1. **Zero Runtime Overhead**: Everything compiles down to plain HTML, CSS, and vanilla JS. It loads instantly and requires zero server maintenance.
2. **Markdown-First Workflow**: Writing an article or tutorial is as simple as creating a `.md` file in the `_posts` folder.
3. **Ruby Simplicity**: Bundler manages dependencies cleanly, making local testing reproducible across any machine.
4. **Git-Driven Deployments**: Pushing to the `main` branch triggers a GitHub Actions workflow that builds the site and serves it via GitHub Pages with HTTPS.

```ruby
# The simplicity of static sites
def publish_post(title)
  puts "Push to main -> GHA builds -> deployed to abelcreates.com!"
end
```

### What's Next?

I'll be posting updates on projects, architecture deep-dives, and tutorials here regularly. Stay tuned!
