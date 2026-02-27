# João Mendes Blog

A personal blog built with [Jekyll](https://jekyllrb.com/) and hosted on [GitHub Pages](https://pages.github.com/).

## 🚀 Quick Start

### Prerequisites

- [Ruby](https://www.ruby-lang.org/) (>= 3.0)
- [Bundler](https://bundler.io/)

### Local Development

```bash
# Install dependencies
bundle install

# Serve locally with live reload
bundle exec jekyll serve --livereload
```

Visit `http://localhost:4000` to preview the site.

### Writing a New Post

Create a new file in `_posts/` with the naming convention:

```
YYYY-MM-DD-your-post-title.md
```

Add front matter at the top:

```yaml
---
layout: post
title: "Your Post Title"
date: 2026-02-27 10:00:00 -0000
categories: [category]
tags: [tag1, tag2]
excerpt: "A brief description of your post."
---

Your content here...
```

## 📁 Project Structure

```
├── _config.yml          # Site configuration
├── _layouts/            # HTML layouts
│   ├── default.html     # Base layout
│   ├── home.html        # Homepage layout
│   ├── page.html        # Static page layout
│   └── post.html        # Blog post layout
├── _posts/              # Blog posts (Markdown)
├── assets/
│   └── css/
│       └── style.css    # Custom styles
├── .github/
│   └── workflows/
│       └── jekyll-pages.yml  # GitHub Actions deployment
├── index.html           # Homepage
├── blog.html            # Blog listing page
├── about.md             # About page
├── 404.html             # Custom 404 page
├── Gemfile              # Ruby dependencies
└── README.md            # This file
```

## 🌐 Deployment

The blog is automatically deployed to GitHub Pages via GitHub Actions on every push to `main`.

### Setup GitHub Pages

1. Go to your repository **Settings** → **Pages**
2. Under **Build and deployment**, select **GitHub Actions** as the source
3. Push to `main` and the workflow will build and deploy automatically

## 📝 License

Content is © João Mendes. The blog engine (Jekyll) is open source under the [MIT License](https://opensource.org/licenses/MIT).
