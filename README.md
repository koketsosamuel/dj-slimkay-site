# DJ Slimkay Site

Astro static site deployed to Cloudflare Workers (Static Assets).

## Develop

```sh
npm install
npm run dev
```

## Deploy

Builds `dist/` and uploads it to Cloudflare as a Workers Static Assets project.

```sh
npm run deploy
```

First-time setup: `npx wrangler login`.

Config lives in `wrangler.jsonc` — worker name, compatibility date, and the `dist/` assets directory.
