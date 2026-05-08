# M4rkyu.com — Legacy Archive

> **Archived.** This is the original Vite + React 18 portfolio for
> [m4rkyu.com](https://m4rkyu.com). The active site has moved to a Next.js
> rebuild at [zhenxiao-yu/M4rkyu.com](https://github.com/zhenxiao-yu/M4rkyu.com).
>
> Vercel keeps deploying this repo to a free `*.vercel.app` URL so the legacy
> build remains reachable for reference. No further feature work is planned
> here.

## Stack

Vite, React 18, JavaScript/JSX, React Router v5, custom CSS, styled-components,
Firebase 10, and the original animation libraries.

## Local Development

```bash
npm install
npm start
npm run build
npm run preview
```

Environment variables for the legacy app live in `.env`, copied from
`.env.example`. Firebase config is read from `VITE_FIREBASE_*` variables.

## Deployment

Pushes to `main` auto-deploy to the `archive-m4rkyu-portfolio` Vercel project.
The custom domain `m4rkyu.com` is no longer attached to this project.

## Rollback Notes

If the active Next.js site needs to be reverted, point the `m4rkyu.com` and
`www.m4rkyu.com` domains back at the latest production deployment of this
project in the Vercel dashboard. The last known-good production deploy is
preserved on Vercel.

## License

MIT — see [LICENSE](LICENSE).
