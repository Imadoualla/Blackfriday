# Black Friday pricing card: shortlisted designs

A static page: `index.html` plus the `assets/bf` folder. No build step.

## Deploy

1. Create a GitHub repository and upload everything in this folder (keep `assets/bf` next to `index.html`).
2. Host it from that repository:
   - **GitHub Pages:** Settings → Pages → Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
   - **Vercel or Netlify:** import the repository; framework "Other", no build command, output folder `/`.

## Options

- Four designs, V1–V4, switched from the list in the top-left corner (or ← / →). `?design=v1` … `?design=v4` opens one directly.
- Opens in red. The round button next to the close button switches to yellow; `?color=yellow` opens it yellow.
- The close button links to `#`; set its `href` in `index.html` to the page it should go back to.
- The "Get Started" buttons link to `#checkout` and are not wired to checkout yet.
