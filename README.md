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

## Writing desk (your private writing app)
Open **https://oliversbulgacs.github.io/write/** on any device.

- It has four baskets: **Drafts → Writing → Editing → Published**. Move a piece by dragging it (on a computer) or with the menu on its card or at the top of the editor.
- Your pieces are saved as Markdown files in your **private** repo `oliversbulgacs/oliversbulgacs`, in the `writing/` folder. Each file's `status:` line records which basket it's in.
- Moving a piece to **Published** copies it to `_posts/` in this public repo, and GitHub Pages puts it on the site in about a minute. Moving it out of Published deletes that copy, so it disappears from the site. The original stays in your private repo.
- The page at /write/ is public, but it's only an empty shell. Without your token it can't read or change anything.
- Your token is stored only in the browser you pasted it into. "Lock" forgets it on that device. If you lose a device, delete the token on GitHub (Settings → Developer settings → Personal access tokens) and make a new one.
