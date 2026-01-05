# Context Window Blog

A Jekyll-powered blog hosted on GitHub Pages.

## Local Development

To run this site locally:

1. Install Ruby and Bundler
2. Install dependencies:
   ```bash
   bundle install
   ```
3. Run the Jekyll server:
   ```bash
   bundle exec jekyll serve
   ```
4. Visit `http://localhost:4000` in your browser

## GitHub Pages Setup

This site is configured to work with GitHub Pages. To enable it:

1. Go to your repository settings
2. Navigate to "Pages" in the sidebar
3. Under "Source", select the branch you want to deploy (usually `main`)
4. Click "Save"

Your site will be published at `https://<username>.github.io/<repository-name>/`

## Adding New Posts

Create a new file in the `_posts` directory with the format:
```
YYYY-MM-DD-title-of-post.md
```

Include front matter at the top:
```yaml
---
layout: post
title: "Your Post Title"
date: YYYY-MM-DD HH:MM:SS -0000
categories: category1 category2
---
```

## License

This work is licensed under a Creative Commons Attribution 4.0 International License.
