# AI Tools Directory

A lightweight, responsive AI tools directory built with plain HTML and Tailwind CSS. There is no framework, build step, or custom JavaScript.

## Run locally

Open `index.html` in a browser, or serve the project root with any static file server. Tailwind CSS is loaded from its CDN, so an internet connection is needed for the styles.

## Pages

- `index.html` — home page and featured tools
- `pages/tools.html` — directory listing
- `pages/categories.html` — category browser
- `pages/tool-details.html` — example tool details
- `pages/about.html` — about page
- `pages/contact.html` — contact form layout
- `pages/login.html` and `pages/register.html` — account form layouts

The HTML fragments in `components/` are copy-ready examples. Plain HTML cannot include shared fragments dynamically without a server-side include mechanism or JavaScript, so the pages currently contain their own navigation and footer markup.

## Notes

The directory content is static sample data. Search forms, contact submission, and account forms are visual/HTML-only and need a backend or external service to become functional. The `assets/images/` and `assets/icons/` directories are reserved for project assets.
