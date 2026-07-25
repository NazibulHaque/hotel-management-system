# Casa Ulika — Static Website (ICT726 Assignment 3)

## Structure
```
casa-ulika/
├── index.html          Home page
├── about.html           Business story + timeline
├── rooms.html            Room & suite listings
├── gallery.html          Media page with filterable, click-to-enlarge gallery
├── testimonials.html    Guest reviews
├── contact.html          Contact info + validated booking-enquiry form
├── css/styles.css       Single external stylesheet (design tokens + all components)
└── js/script.js          Mobile nav, gallery lightbox, form validation
```

## How to view it
No build step needed. Open `index.html` directly in a browser, or serve the
folder locally, e.g. `python3 -m http.server` from inside `casa-ulika/`, then
visit `http://localhost:8000`.

## Requirements checklist (for your own reference)
- Homepage is `index.html`, states business name + a short paragraph. ✔
- Contact page has a `<form>`, styled with CSS, with HTML5 + JS validation
  and visible success/error feedback (no PHP / server-side code). ✔
- 4 additional pages beyond Home + Contact (About, Rooms, Gallery,
  Testimonials) — more than the minimum 3 required. ✔
- Media page (`gallery.html`) has thumbnails that open a larger version on
  click, plus a category filter. ✔
- One external stylesheet only (max 2 allowed). ✔
- 5 CSS3 techniques used (only 3 required): transitions, transforms
  (scale/rotate on hover), rounded corners, shadows, and gradients. ✔
- Responsive via media queries at 900px / 680px / 420px breakpoints,
  including a hamburger nav on small screens. ✔
- Accessibility: skip link, semantic landmarks (`header`/`nav`/`main`/
  `footer`), `alt` text on every image, `aria-current`, `aria-live` on form
  feedback, `aria-pressed` on filters, visible focus states, and
  `prefers-reduced-motion` support. ✔
- No frameworks/templates (Bootstrap etc.) — everything hand-written. ✔
- No server-side scripting (PHP/ASP) — this is a static prototype only. ✔
