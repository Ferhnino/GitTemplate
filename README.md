# Portfolio site

A single-page portfolio built around your SOC/security work, meant to be hosted on GitHub Pages.

## Before you publish

Search each file for `EDIT:` comments and fill in your own details:

- **`index.html`**
  - Your name (page `<title>` and the hero heading)
  - The bio paragraph in the About section — reword it in your own voice
  - Contact links at the bottom (email, GitHub, LinkedIn)

Everything else (the `threat-feed-lite` write-up, connector table, skills list) is drawn from what
you've actually built — edit freely if anything should be trimmed, corrected, or expanded.

## Deploying to GitHub Pages

1. Create a new repository on GitHub (e.g. `yourusername.github.io` for a root-level personal site,
   or any repo name for a project page).
2. Add `index.html` and `style.css` to the repo root and push them.
3. In the repo, go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to "Deploy from a branch," pick the `main` branch
   and the `/ (root)` folder, then save.
5. GitHub will publish the site at `https://yourusername.github.io` (if you named the repo that way)
   or `https://yourusername.github.io/repo-name` otherwise. It usually takes a minute or two to go live.

## Adding more projects later

Each "featured build" follows the same shape in `index.html`: a `<section class="section">` with a
tagline, a short problem/approach/outcome narrative (`.story` block), and an optional data table. Copy
the `#build` section as a template for the next one, and add a nav link for it alongside `About` /
`Build` / `Skills` / `Contact`.
