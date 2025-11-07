# Sacred Return

Sacred Return is a deeply intuitive, ceremonial brand devoted to postpartum mothers in their first year after birth. It offers a soulful alternative to traditional recovery programs with poetic movement, ritual, guided meditations, journaling, and music — inviting mothers to reconnect with their bodies softly, slowly, and sacredly.

## Vision

- **Mission:** Create a sacred space for new mothers to reconnect with their bodies and essence through presence, breath, and beauty — never pressure or performance.
- **Tone & Aesthetic:** Earthy, feminine tones (clay, sand, rose, sage, cream), organic textures, and spacious minimal design that feels maternal, raw, and magical.
- **Keywords:** Reverent · Rooted · Intuitive · Poetic · Sacred · Slow · Feminine · Embodied · Gentle · Transformative · Ancestral

## Live Site

- Source: `index.html`
- Deployment: GitHub Pages from the `main` branch (see workflow in `.github/workflows/pages.yml`)

Once the repository is connected to GitHub:

1. Go to **Settings → Pages**.
2. Under **Build and deployment**, ensure **Source** is set to “GitHub Actions”.
3. The `Deploy to GitHub Pages` workflow will publish the site on every push to `main`.

## Local Development

```bash
git clone <your-fork-or-remote-url>
cd sacred-return
npm install # only if you add tooling later; not required for static HTML
open index.html # or use your preferred static server
```

Because this is a static site, you can simply open `index.html` in any modern browser, or run a lightweight server such as `python3 -m http.server`.

## Creating the GitHub Repository

If this directory is new on your machine you can initialise and connect it to GitHub with:

```bash
git init -b main
git add .
git commit -m "Initial commit for Sacred Return site"
git remote add origin git@github.com:<your-username>/sacred-return.git
git push -u origin main
```

After pushing, open the repository on GitHub to validate that the GitHub Pages workflow succeeded. The published site URL will appear under the latest workflow run and in **Settings → Pages**.

## Customisation Notes

- Update imagery by replacing the background image reference in the `.hero-image .orb` CSS rule within `index.html`.
- Tailor the waitlist form to your email platform (e.g., ConvertKit, Mailchimp, Flodesk) by swapping the form action/inputs.
- Extend the site by adding additional HTML sections or linking to course/payment platforms; all styling is inline for an easy starting point.

---

You are worthy. You belong. You are not alone. This is your sacred return. 
