# Kyn — static site

Deploy to Vercel:

```bash
npm i -g vercel
cd dist
vercel
```

Or drag-and-drop the `dist` folder at https://vercel.com/new.

## Routes
- `/` — Landing page
- `/run` — Live demo (Run View)
- `/design-system` — Design system reference

`vercel.json` enables clean URLs (no .html extensions).

## Local preview
Any static server works:
```bash
npx serve dist
```
