
# NerdWyrm Nature Journal (Jekyll on GitHub Pages)

A lightweight, zero-maintenance blog for field notes. Built with the `minima` theme and GitHub Pages–supported plugins.

## Local preview (optional)
If you want to run this locally, install Ruby and Bundler, then:
```bash
bundle install
bundle exec jekyll serve
```
Your site will be at http://localhost:4000

## Write a new post
1. Copy `_drafts/_TEMPLATE.md` to `_drafts/your-title.md`
2. Edit the front matter and content
3. When ready, move it to `_posts/` and rename it `YYYY-MM-DD-your-title.md`

## Deploy to GitHub Pages
- Push this repository to GitHub
- Enable **Pages** in repository settings
- Set the **Custom domain** to `nerdwyrm.com` (creates `CNAME`)
- Ensure HTTPS is enforced after DNS propagates
