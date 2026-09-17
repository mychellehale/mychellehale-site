# mychellehale.com

Personal site for Mychelle Hale, Senior Principal Data Scientist.

Five static HTML pages with a shared stylesheet. Deployed via Cloudflare Workers (static assets), not Pages. Config in `wrangler.jsonc`, worker name `mychellehale-site`, serving `./public`.

## Pages

- `public/index.html` — home
- `public/about.html` — about
- `public/projects.html` — projects
- `public/speaking.html` — speaking
- `public/writing.html` — writing
- `public/contact.html` — contact
- `public/style.css` — shared styles

## Deploying

Any push to `main` triggers an automatic redeploy (~1-2 min).
