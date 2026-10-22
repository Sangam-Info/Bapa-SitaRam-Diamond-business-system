# Bapa Sitaram Diamond — static prototype

Deployed to Cloudflare Workers (static assets) via `npx wrangler deploy`.

Repo layout (do not change):
- `wrangler.toml` — at the repo ROOT
- `public/index.html` — the app

The `public` folder MUST be committed and pushed, or the deploy fails with
"assets.directory ... does not exist".
