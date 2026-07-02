# Mohamed Aashiq — Portfolio

A single-page personal portfolio site: a "road journey" timeline running from school
through engineering studies to a career in retail, marketing, and coffee shop operations.

## Run it
Just open `index.html` in any browser — no build step, no server required.

## View it live on GitHub Pages
Push this whole folder to a repo, then enable:
**Settings → Pages → Deploy from branch → main → / (root)**
Your site will then be live at `https://<your-username>.github.io/<repo-name>/`

## Structure
```
.
├── index.html
├── style.css
├── script.js
├── favicon.ico
├── images/
│   ├── DSC01837.jpg
│   ├── FullSizeRender.jpg
│   ├── IMG_0673.jpg
│   ├── IMG_1001.jpg
│   ├── IMG_1609.jpg
│   ├── IMG_1793.jpg
│   └── IMG_7326.jpg
└── README.md
```

## External dependency
The page links to Google Fonts (Unbounded, Work Sans, Space Mono) via CDN for the
type styling. This is the only external resource — if it's unreachable the page
still works, it just falls back to a system font.

## Editing
- Timeline entries live in the `#journey` section of `index.html`.
- All styling is in `style.css` (CSS variables at the top control the color palette).
- The scroll-reveal animation logic is in `script.js`.
- Swap gallery photos by replacing files in `images/` (keep filenames, or update `src` paths in `index.html`).
