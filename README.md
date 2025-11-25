# ChiragFolio

Personal portfolio landing page for Chirag Baldia. The site is a single static HTML file designed for deployment on [Vercel](https://vercel.com/).

## Project structure

```
.
├── index.html              # Main entry point served by Vercel
├── chirag-removebg-preview.png
└── vercel.json             # Static build + rewrite config
```

## Local preview

Because the site is fully static, you can open `index.html` directly in your browser or serve it with any static server, e.g.

```powershell
npx serve .
```

## Deploying to Vercel

1. Install the Vercel CLI if you have not already:
   ```powershell
   npm i -g vercel
   ```
2. Log in to your Vercel account:
   ```powershell
   vercel login
   ```
3. From the project root (`ChiragFolio`), run the initial deploy to create the project:
   ```powershell
   vercel
   ```
   Accept the defaults or customize the project name and scope as needed.
4. For subsequent production deployments, run:
   ```powershell
   vercel --prod
   ```

Vercel automatically detects `index.html` as the entry point, and the included `vercel.json` ensures every route resolves to the static page.
