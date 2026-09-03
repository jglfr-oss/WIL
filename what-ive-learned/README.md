# What I've Learned

Stories from Dad. A static site — no build step.

- `index.html` — landing page
- `stories/` — one HTML file per story
- `favicon.svg`

## Publish

1. Create a GitHub repo called `what-ive-learned` (public or private).
2. Upload everything in this folder (Add file → Upload files → drag the folder contents in). Keep the `stories/` folder.
3. In Vercel: Add New → Project → import the repo. Framework preset: **Other**. Leave build command and output directory blank. Deploy.

## Add a story

Drop a new `.html` file in `stories/`, then copy one of the `<a class="card">` blocks in `index.html` and change the `href`, kicker, title, and blurb.
