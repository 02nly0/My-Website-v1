# Only · Profile

A simple, single-page "link-in-bio" style website with a dark, modern UI. Built with plain HTML, CSS, and JavaScript — no frameworks, no build step.

## Features

- Two-tab layout: **Home** (avatar, bio, social links) and **Projects** (project cards)
- Collapsible Discord section with a lazy-loaded live status embed (via Lanyard)
- Toast notifications
- Custom 403 / 404 / 500 error pages
- Privacy Policy and Terms of Service pages

## Project Structure

```
My-Website-v1/
├── index.html          # Main profile page
├── privacy.html        # Privacy policy
├── terms.html          # Terms of service
├── 403.html            # Access denied page
├── 404.html            # Not found page
├── 500.html            # Server error page
├── assets/
│   ├── css/
│   │   └── style.css   # All styling
│   ├── js/
│   │   └── script.js   # Tab navigation, Discord toggle, toasts
│   └── img/
│       └── avatar.jpg  # Profile picture
└── README.md
```

## Getting Started

No build tools required — it's static HTML/CSS/JS.

1. Clone or download this repository.
2. Open `index.html` in your browser, or serve the folder with any static file server (e.g. `npx serve`, GitHub Pages, Netlify, Vercel).

## Customization

- **Profile info & links**: edit the `avatar-section`, `bio`, and `links-list` blocks in `index.html`.
- **Projects**: copy or edit a `.project-card` block inside `projectsGrid` in `index.html`.
- **Styling**: all colors, fonts, and layout live in `assets/css/style.css`.
- **Behavior**: tab switching and the Discord accordion are handled in `assets/js/script.js`.

## Tech Stack

- HTML5 / CSS3 / vanilla JavaScript
- [Lucide](https://lucide.dev) for icons
- [Font Awesome](https://fontawesome.com) (brand icons only: Instagram, GitHub, Discord)
- [Lanyard](https://github.com/Phineas/lanyard) for the live Discord status embed
- Google Fonts (JetBrains Mono)

## License

Personal project — feel free to fork and adapt for your own profile page.
