# lokeshleel.github.io

Personal landing page for **Lokesh Leel — Product Manager**, served at [lokeshleel.space](https://lokeshleel.space).

Hosted via [GitHub Pages](https://pages.github.com/). No build step, no framework — pure HTML + CSS.

---

## 🗂 Structure

```
.
├── index.html   # All page content
├── style.css    # Styles (dark palette, Inter font, animations)
├── CNAME        # Custom domain mapping
└── README.md    # This file
```

---

## ✏️ How to Update Content

### Adding a Project
Open `index.html` and find the `#projects` section. Copy one of the `.card` blocks and fill in:
- `.card-tag` — category label (e.g. `B2C · Mobile`)
- `.card-title` — project name
- `.card-desc` — 1–2 sentence description
- `.chip` elements — relevant tags
- `.card-link` — change `href="#"` to your project URL and add class `active`

### Adding a Case Study
Find the `#case-studies` section. Copy a `.case-card` block and update:
- `.case-num` — `01`, `02`, `03`…
- `.case-title` — title
- `.case-teaser` — short teaser paragraph
- `.card-link` — link to the case study doc

### Publishing a Thought
Find the `#thoughts` section. Copy a `.thought-item` block and fill in:
- `.thought-date` — e.g. `June 2026`
- `.thought-title` — headline
- `.thought-excerpt` — 2–3 sentence preview
- `.thought-link` — link to the post; add class `active` to enable it

---

## 🌐 Custom Domain Setup

1. In this repo's **Settings → Pages**, set the custom domain to `lokeshleel.space`.
2. At your DNS provider, add the following **A records** pointing to GitHub's IPs:

   ```
   185.199.108.153
   185.199.109.153
   185.199.110.153
   185.199.111.153
   ```

3. Add a **CNAME record**: `www` → `lokeshleel.github.io`

The `CNAME` file in this repo root is already configured.
