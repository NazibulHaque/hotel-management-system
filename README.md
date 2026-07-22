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

## Important — before you submit
1. **Images are placeholders.** Every photo currently points to
   `picsum.photos` (a free stock-photo hotlinking service) so the site is
   fully functional out of the box. The assignment requires all media to be
   self-created, royalty-free, or ethically sourced with proper hosting —
   swap these `<img src="https://picsum.photos/...">` URLs for your own
   photos (or licensed royalty-free images, e.g. from Pexels/Unsplash
   downloaded and saved into an `images/` folder) before you submit, and
   update the `alt` text if the image changes.
2. **AI Assistance Declaration.** The brief requires you to declare AI use
   in your report with side-by-side before/after examples. Keep notes as
   you customize this: content you rewrote, colors/fonts you changed, extra
   sections you added, bugs you fixed yourself, etc. — that's what goes in
   Section 2 of the report.
3. **Host it.** Push this folder to GitHub Pages, Netlify, or similar, and
   put the live link in your Moodle submission.
4. **Business name/content.** "Casa Ulika" and its story are invented for
   this brief — swap in your actual assigned business's name, story, and
   real contact details throughout.
