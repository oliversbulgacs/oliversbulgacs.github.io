# My site

A simple personal site and blog built with Jekyll, which GitHub Pages builds automatically.

## Write a new post
1. Add a file to `_posts/` named `YYYY-MM-DD-some-title.md`, for example `2026-11-10-my-second-post.md`.
2. Start it with:
   ```
   ---
   layout: post
   title: My second post
   ---
   ```
3. Write the post in Markdown below that, then commit and push. It goes live within about a minute.

## Edit your details
- Name, tagline and links: `_config.yml`
- About page: `about.md`

## Going public
At the moment `hide_from_search: true` in `_config.yml` asks search engines not to list the site. Anyone you give the link to can still read it.
When you're ready to be found, change that line to `false` and push.
