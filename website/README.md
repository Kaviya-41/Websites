# Bakkery Site — Vercel Deployment

This is a small static site. The repository includes a `vercel.json` config and a `package.json` script to simplify deployment.

Quick deploy (CLI):

1. Install the Vercel CLI or use npx:

```bash
npm install -g vercel
# or
npx vercel
```

2. Log in to Vercel:

```bash
vercel login
```

3. Deploy to production:

```bash
vercel --prod
```

Or, connect your GitHub repository to Vercel in the Vercel dashboard and import the project.

Files added:

- `vercel.json` — static build + route to `bakkery.html`
- `package.json` — `npm run deploy` runs `vercel --prod`
