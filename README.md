# Serena Lee Photography

One-page portfolio site for freelance wedding and portrait photographer Serena Lee. Plain HTML and CSS, no build step.

## Structure

- `index.html` is the whole site: hero, six-photo portfolio grid, about and contact.
- `images/` holds the portfolio photos.
- `vercel.json` sets caching and basic security headers.

## Add a photo

Drop the file in `images/`, then replace a placeholder in `index.html`:

```html
<span class="shot"><img src="images/your-photo.jpg" alt="Describe the photo" loading="lazy"></span>
```

## Deploy on Vercel

1. Import this repo at https://vercel.com/new.
2. Leave Framework Preset as **Other**. Leave the build command and output directory empty.
3. Deploy. Every push to `main` redeploys.

Or from the terminal: `npx vercel --prod`.

## Preview locally

`python3 -m http.server 3000`, then open http://localhost:3000.
