# hello-mr-anderson

> Smoke-test scaffold built by Mr. Anderson Dev — the first autonomous build.

## Stack

| Layer | Tool |
|-------|------|
| Bundler | [Vite](https://vitejs.dev/) v5 |
| Language | Vanilla JavaScript (ES Modules) |
| Styles | Plain CSS |
| Deployment | Netlify |

## Quick Start

```bash
# 1. Install dependencies
npm install

# 2. Start dev server (hot-reload)
npm run dev

# 3. Production build → dist/
npm run build

# 4. Preview production build locally
npm run preview
```

## Netlify Deployment

The repo includes a `netlify.toml` that instructs Netlify to:

- Run `npm run build`
- Publish the `dist/` directory

Link the GitHub repo to your Netlify site via the Netlify dashboard, or push manually using the Netlify CLI:

```bash
npx netlify deploy --prod --dir=dist
```

## Environment Variables

No environment variables are required for this project.

## Live URL

http://hello-mr-anderson-mofscbzh.netlify.app
