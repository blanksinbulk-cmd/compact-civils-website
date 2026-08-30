# Compact Civils — Website Package

## What's inside
- index.html      — Home
- about.html      — About Us
- services.html   — Services
- projects.html   — Projects (with working filter buttons)
- contact.html    — Contact

## How to use it
1. Unzip this folder.
2. Double-click index.html to preview the site in your browser — it works immediately, no build step or server required.
3. To publish it, upload all 5 files (keeping them in the same folder, same filenames) to any static host: Netlify, Vercel, GitHub Pages, cPanel, etc. Just make sure index.html stays at the root.

## Before going live, do these two things

### 1. Connect the forms (Request a Quote + Contact page)
Both forms currently show a "not connected yet" message instead of sending anywhere. To fix:
1. Sign up free at https://formspree.io
2. Create two forms — one for quote requests, one for general contact
3. Copy each form's endpoint (looks like https://formspree.io/f/abcdwxyz)
4. Open index.html in a text editor, find `QUOTE_FORM_ENDPOINT` near the bottom, and paste in your quote endpoint
5. Open contact.html, find `CONTACT_FORM_ENDPOINT`, and paste in your contact endpoint
6. Formspree emails you every submission — no server code needed

### 2. Swap in your real business details
Search each file for these placeholders and replace with your actual info:
- +27 00 000 0000        → your phone number
- info@compactcivils.co.za → your email
- 123 Industrial Road, Johannesburg → your address
- wa.me/27000000000       → your WhatsApp number (used in the floating WhatsApp button and Contact page)

## Notes
- Built with Tailwind CSS (loaded via CDN) — no npm install or build step needed.
- All photos are free-license Unsplash images, verified working.
- Fully responsive — tested down to mobile widths.
