# GRN Commerce Next.js Starter

A curated Next.js starter template for [GRN Commerce](https://grncommerce.com) customers.

Originally derived from [`vercel/next.js/examples/blog-starter`](https://github.com/vercel/next.js/tree/canary/examples/blog-starter); customized as a GRN Commerce blueprint. Ideal for content-shaped sites with markdown posts, but flexible enough to evolve into any Next.js app.

## Deploy this template

Sign in at [app.grncommerce.com](https://app.grncommerce.com), open **Templates**, pick **Next.js**, fill in your subdomain and tier, then click **Deploy**. Your site lands at `<your-slug>.grncommerce.com` in roughly two minutes.

## What you get

- Next.js with App Router, TypeScript, Tailwind CSS
- Markdown post pipeline (`_posts/`) with `gray-matter` + `remark`
- Static / SSR build via `next build`
- AutoSSL on your `<slug>.grncommerce.com` subdomain
- Atomic deploys via the GRN Commerce build pipeline

## Build commands

```bash
pnpm install
pnpm build
```

Output directory: `.next/`. Node version: 20 LTS.

## Note

This repository is a read-only blueprint. Each customer site is forked from this seed at provision time into a server-managed bare repository — you don't push to this repo directly. To connect your own GitHub remote for code edits, ask your GRN Commerce contact about the "Connect your own GitHub" flow (ftr-058, scheduled).

— GRN Commerce
