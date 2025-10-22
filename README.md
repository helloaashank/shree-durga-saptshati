# Shree Durga Saptshati Website

Status tracker (update as features evolve):

- [x] Create dedicated Buy Now page with matching theme
- [x] Redirect Buy Now button to the Buy page
- [x] Buy page header: "सनातन पूजा पद्धति", book image, Contact link to Facebook story URL
- [x] Add homepage Reviews section
- [x] Add homepage FAQs section (sample Q&A)
- [x] Add new navigation items/pages: Drik Panchang, Festivals, Scripture Books, Bhajans
- [x] Add basic Auth UI (Sign in page + Google login placeholder)
- [x] Collect basic user info placeholders (name, email, phone) on sign up page
- [x] Disable right-click and common copy/paste shortcuts on web
- [x] Responsive layout across devices (mobile/tablet/desktop)
- [x] Robust dark mode support (prefers-color-scheme)
- [ ] Hook up real backend/Auth provider (Google OAuth)
- [ ] Content population for new pages
- [ ] Improve accessibility and SEO metadata

## Development

Static HTML/CSS site. Open index.html in a browser. All subpages share the same stylesheet.

Checklist for future edits:
- Ensure new components are responsive: use grid/flex with wrap and mobile breakpoints at 992px/768px/480px.
- Test dark mode: verify colors derive from CSS variables and surfaces adapt under prefers-color-scheme: dark.
- Keep navigation usable on small screens (wrap and center).
- Avoid fixed widths; prefer max-width and relative spacing.

## Pages
- index.html: Home, About, Privacy, Reviews, FAQs
- buy.html: Buy page with book details and Contact CTA
- drik-panchang.html, festivals.html, scriptures.html, bhajans.html: Topic pages (stubs)
- auth.html: Sign in/Sign up UI (front-end only)

## Notes
- Right-click context menu is disabled and common keyboard shortcuts for copy/cut/paste/view-source are blocked via JS.
- Replace placeholders and integrate a real auth flow when ready.
