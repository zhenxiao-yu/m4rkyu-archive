# Agent Guidance — Legacy Archive

This repository is the archived Vite + React 18 portfolio for m4rkyu.com.
It is no longer actively developed. The active site lives at
[zhenxiao-yu/M4rkyu.com](https://github.com/zhenxiao-yu/M4rkyu.com) (Next.js).

## Scope

- Treat this repo as frozen. Only land narrow fixes (security patches,
  one-off content edits) — not feature work, refactors, or modernization.
- Do not introduce TypeScript, Next.js, Tailwind, or any other stack change.
- Do not delete the app or repoint domains without explicit instruction.

## Stack Rules

- JavaScript/JSX only. Do not create `.ts` or `.tsx` files.
- React Router v5: use `<Switch>`, `<Route>`, `useHistory`, `useLocation`,
  `NavLink`. Do not migrate to React Router v6 conventions.
- Framer Motion v4 API. Do not adopt newer API patterns.
- Firebase config is read from `VITE_FIREBASE_*` environment variables.
- `dist/` is generated output. Do not edit it directly.

## Content Safety

Keep private phone number and home address information out of source,
fixtures, public content, placeholder text, screenshots, and generated assets.

## Commands

```bash
npm install
npm start
npm run build
npm run preview
```
