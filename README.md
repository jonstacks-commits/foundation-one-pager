# foundation-one-pager

Standalone landing page for **The Specialized Foundation's** Riding for Focus one-pager. Isolated from `stacksadvisory` — separate repo, separate GitHub Pages site.

Live at: `https://jonstacks-commits.github.io/foundation-one-pager/`

## What's here

```
foundation-one-pager/
├── index.html                       # landing page: embeds the PDF, view/download buttons
├── styles.css                       # Specialized Foundation teal/black/white palette
├── assets/
│   ├── TSF-One-Pager-DRAFT.pdf      # source document
│   └── tsf-preview.jpg              # page-1 thumbnail, used for link previews (og:image)
└── README.md
```

## Deploy

1. Create a **public** repo named `foundation-one-pager` under `jonstacks-commits`.
   (GitHub Pages on a free/personal account can't serve a private repo publicly — public is required for this to work as a shareable link.)
2. Push these four files/folders as-is — no build step.
3. In the repo: **Settings → Pages → Deploy from a branch → `main` / root**.
4. Give it a minute, then check `https://jonstacks-commits.github.io/foundation-one-pager/` on both desktop and mobile.
5. To use as a link preview (email, LinkedIn), share the page URL, not the PDF URL directly — the `og:image` tag in `index.html` is what makes the thumbnail render.

## Before making the repo public

The PDF and this page carry **Specialized Foundation** branding, staff quotes (Lawrence Kovacs, Anne Rock, Jesse Sorenson), and photographs of students. Confirm you have the Foundation's sign-off to publish these externally before flipping the repo to public — once Pages is live, the PDF and image in `assets/` are publicly fetchable regardless of any link-sharing controls on the page itself.

## Reusing this pattern

Later foundation pages (`riding-for-focus`, `cycling-research-preview`, etc.) can follow the same shape: one repo per deliverable, `index.html` + `styles.css` + `assets/`, deployed via Pages from `main`.
