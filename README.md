# Mr Kool Snow Cone, Ice Cream and Snack — Website

Static marketing + booking site for Mr Kool, a mobile snow cone, ice cream and
snack truck serving the Cayman Islands island-wide.

## Stack
- Hand-coded static HTML/CSS/JS — no build step
- Hosted on Netlify (publish directory: repo root, see `netlify.toml`)
- Booking form uses **Netlify Forms** (form name: `event-booking`) with a
  honeypot field for spam protection; submissions should be routed to
  `snowsnacks@gmail.com` via a form notification in the Netlify dashboard
  (Site → Forms → Notifications)

## Pages
- `/` — Home (hero, offerings, event types, Instagram pointer, booking CTA)
- `/services/` — Services & Products (menu groups + event service)
- `/contact/` — Contact + booking form (primary CTA target)
- `/success/` — Form submission confirmation (noindex)

## Brand
Palette derived from the logo (pending client sign-off):
blue `#1E88D2` · sand `#FBF6EE` · ink `#1A1F24` · green `#3FA644` (CTAs) ·
red `#D62828` / yellow `#FFC93C` (small accents). Headings: Baloo 2,
body: Nunito (Google Fonts).

The logo image is hotlinked from the client's uploaded asset URL on the
Contact page; replace with a locally hosted, cleaned/cropped version when
final brand assets are supplied. No truck/product photos were provided —
the design is intentionally photo-independent (CSS/SVG art).
