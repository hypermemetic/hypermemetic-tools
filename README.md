# hypermemetic-tools

The `hypermemetic.ai` (apex) tools page. Astro static site, deployed
through plexus-platform's `site_add_from_repo` reading
`.hyperforge/platform.toml`.

## Local dev

```
npm install
npm run dev
```

## Deploy

```
synapse platform site_add_from_repo --tenant hypermemetic --repo .
synapse platform site_redeploy --tenant hypermemetic --name tools
```
