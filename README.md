# semrush-aem-plg

Static presales redesign reports and prototypes, deployed via GitHub Pages.

## Live site

Landing page → `index.html` links to each project report.

## Structure

```
.
├── index.html              ← landing page (links to all reports)
├── knack/                  ← Knack uplift (report + 4 prototypes + assets)
│   ├── index.html          ← redesign report
│   ├── home-A-proposed.html  · Variant A (faithful + improvements)
│   ├── home-B-proposed.html  · Variant B
│   ├── home-C-cinematic.html · Variant C (motion)
│   ├── home-C-proposed.html  · Variant C static fallback
│   └── assets/
├── moneyhub/               ← Moneyhub uplift
└── cecreditsonline/        ← CE Credits Online uplift
```

Each project folder is self-contained. Web fonts load from Google Fonts;
all other assets are local.

## Notes

Brand-faithful presales explorations generated with the stardust uplift
pipeline. Visuals reuse captured brand assets; any figure shown as a
placeholder should be verified before production use.
