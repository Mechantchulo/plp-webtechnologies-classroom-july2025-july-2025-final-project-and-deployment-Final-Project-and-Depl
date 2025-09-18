
# Savory Bites — Fine Dining Restaurant Website

Savory Bites is a responsive, multi‑page restaurant website showcasing a refined dining experience, curated menu highlights, a rich photo gallery, and clear contact and reservation pathways. The project is built with semantic HTML5, modern CSS, and vanilla JavaScript for interactivity and accessibility.

Live URL: add-once-deployed

## Features

- Elegant, responsive UI with consistent header, navigation, and footer
- Mobile hamburger navigation and smooth scrolling
- Scroll-triggered animations for engaging content reveal
- Menu preview on the homepage with call-to-actions to view the full menu
- Filterable image gallery with a lightbox (next/prev, captions, keyboard controls)
- Contact/reservations form with client-side validation and helpful inline errors
- Performance-friendly images with lazy loading attributes

## Pages

- Home: `index.html`
  - Hero, key features, About preview, and Featured Dishes
- About Us: `pages/about.html`
  - Story, mission & values, team, awards, and testimonials
- Gallery: `pages/gallery.html`
  - Filter by category (dishes, interior, events) and view images in a lightbox
- Menu: `pages/menu.html` (linked, ensure present)
- Contact: `pages/contact.html` (linked, ensure present)

## Tech Stack

- HTML5 for structure and semantics
- CSS3 for layout, theming, and animations (`css/styles.css`)
- Vanilla JavaScript for interactivity (`js/main.js`)
- Google Fonts: Playfair Display, Inter

## Project Structure

```
root/
├── index.html
├── pages/
│   ├── about.html
│   ├── gallery.html
│   ├── menu.html
│   └── contact.html
├── css/
│   └── styles.css
├── js/
│   └── main.js
└── images/
    ├── dish1.jpeg, dish2.jpeg, dish3.jpeg, dish4.jpeg
    ├── interior.jpeg
    ├── meetevent.jpeg
    ├── restaurant-event.jpeg
    └── about/, gallery/ ...
```

Key files:

- `index.html`: Homepage layout and navigation
- `pages/about.html`: Story, values, team, awards, testimonials
- `pages/gallery.html`: Filterable gallery + lightbox markup
- `css/styles.css`: Global styles, responsive layout, components, lightbox
- `js/main.js`: Navigation, smooth scroll, intersection-based animations, gallery filter, lightbox, contact form validation

## Getting Started (Local Development)

1. Clone or download this repository
2. Open `index.html` in your browser
   - Tip: Use a simple local server for best results (paths, caching)
     - VS Code extension: Live Server
     - Python: `python3 -m http.server` and open `http://localhost:8000`

## Deployment

This is a static site, so you can deploy anywhere that serves static files:

- GitHub Pages
  - Push to a public repo
  - In repo settings, enable Pages (root folder)
- Netlify
  - Drag-and-drop the project folder in the Netlify dashboard, or link the repo
- Vercel
  - Import the repo and deploy without a build step

After deployment, update the Live URL at the top of this README.

## Accessibility & Best Practices

- Semantic HTML5 tags for better screen reader support
- Alt text on images and descriptive link text
- Keyboard-friendly lightbox navigation (Esc, Arrow keys)
- Color contrast mindful styling

## Screenshots (Optional)

Add screenshots in `images/` and reference them here, for example:

```
![Homepage Hero](images/interior.jpeg)
![Featured Dish](images/dish1.jpeg)
```

## Credits

- Design and development: Your Name
- Images: Project assets in `images/` (replace with your own or royalty-free sources)

## License

This project is for educational and portfolio purposes. If you plan to use it commercially, replace media assets with licensed content and review third-party licenses.
