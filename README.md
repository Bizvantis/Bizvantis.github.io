# J Pranay Siddarth - Portfolio

Personal portfolio website: about me, goals, experience, research papers, projects, achievements and skills.

**Live site:** https://bizvantis.github.io/

## Structure

| Path | What it is |
|---|---|
| `index.html` | The whole page: every section and all the text |
| `css/style.css` | Layout, colours (light and dark theme) and responsive rules |
| `js/main.js` | Theme toggle, mobile menu, scroll animations, active nav link |
| `assets/favicon.svg` | Browser-tab icon |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |

It is plain HTML, CSS and JavaScript: no build step and no dependencies apart from Google Fonts.

## Edit the content

Open `index.html` in any editor (for example VS Code). Each section is marked with a comment:
`<!-- HERO -->`, `<!-- ABOUT + GOALS -->`, `<!-- EXPERIENCE -->`, `<!-- RESEARCH -->`, `<!-- PROJECTS -->`,
`<!-- ACHIEVEMENTS + LEADERSHIP -->`, `<!-- SKILLS -->`, `<!-- CONTACT -->`.

- **Add a project:** copy one `<article class="project reveal">...</article>` block and change the text and link.
- **Add an achievement:** copy one `<li class="award ...">` block. Use class `gold` for 1st place and `silver` for 2nd.
- **Update a paper's status:** change the `<span class="badge">Manuscript</span>` text (for example to `Under review` or `Published`).

## Preview locally

Double-click `index.html` to open it in your browser.

## Publish changes

The site is served by GitHub Pages from the `main` branch of `github.com/Bizvantis/Bizvantis.github.io`.
After editing, run these from this folder:

```bash
git add -A
git commit -m "Update portfolio"
git push
```

The live site updates within a minute or two.
