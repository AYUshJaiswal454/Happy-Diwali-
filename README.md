# Diwali Deepmala

An interactive Diwali page: light 108 diyas on a river ghat, launch fireworks, write with a sparkler, draw a rangoli and copy a wish for the family group. It is a single static page with no build step.

## Files

- `index.html` – the whole interactive page
- `og-image.jpg` – the preview image WhatsApp and other apps show when the link is shared
- `Shubh-Deepavali-2026.pdf` – the printable greeting card, linked from the page footer
- `render.yaml` – tells Render to publish this folder as a free static site

## Deploy on Render

1. **Put the files on GitHub.** Create a new repository on github.com, choose "uploading an existing file", and drag in all the files from this folder (the files themselves, not the folder). Commit.
2. **Create the site on Render.** In the Render dashboard choose **New → Blueprint** and pick the repository. Render reads `render.yaml` and sets everything up.
   - Or choose **New → Static Site**, pick the repository, leave **Build Command** empty and set **Publish Directory** to `.`
3. **Open your link.** Render gives you an address like `https://diwali-deepmala.onrender.com`. Every push to GitHub redeploys it.

## If your address is different

The share preview uses the address `https://diwali-deepmala.onrender.com`. If Render gives your site a different name, open `index.html` and replace that address in the two lines that start with `<meta property="og:url"` and `<meta property="og:image"`, then commit.
