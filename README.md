# Context Window Blog

A Jekyll-powered blog hosted on GitHub Pages.

See it live on: https://chrisrng.github.io/context-window-blog

## Backlog

- https://addyosmani.com/blog/21-lessons/
- https://www.blog4ems.com/p/why-your-best-engineers-arent-getting-promoted-to-staff-roles
- https://karpathy.bearblog.dev/year-in-review-2025/
- https://abseil.io/fast/hints.html
- https://zhengdongwang.com/2025/12/30/2025-letter.html
- https://snscratchpad.com/posts/looking-ahead-2026/
- https://thinkingmachines.ai/blog/defeating-nondeterminism-in-llm-inference/
- https://ludwigabap.com/posts/on-becoming-competitive-when-joining-a-new-company/
- https://www.seangoedecke.com/taking-a-position/
- https://leaddev.com/leadership/managing-complex-organizational-change
- https://blog.thepete.net/blog/2019/12/09/delivering-on-an-architecture-strategy/

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
