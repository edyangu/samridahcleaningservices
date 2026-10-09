Samridah Cleaning Services

Website for Samridah Cleaning Services, a cleaning company based in Kampala, Uganda.

Live site: https://samridah-website.vercel.app (update after deploying)

WHAT IT DOES

The site shows the company's services and lets clients place orders through a form. Orders are sent by email to samridahservices@gmail.com using Formspree.

SERVICES LISTED

- Residential cleaning (house cleaning, deep cleaning, carpets, windows)
- Commercial cleaning (offices, warehouses, malls, schools, hotels)
- Compound cleaning (sweeping, trimming, lawn mowing, designing)
- Other services (tile cleaning, detergents, air fresheners, toilet supplies)

FILES

- index.html - the whole website
- README.md - this file

HOW IT WORKS

The order form posts to Formspree, which forwards submissions to the company email. No backend or database is used.

The Formspree endpoint is set in index.html:

action="https://formspree.io/f/YOUR_FORM_ID"

Replace YOUR_FORM_ID with the real form ID before deploying.

DEPLOYMENT

Hosted on Vercel. Every push to the main branch deploys automatically. To deploy manually, import the repo at vercel.com/new and click Deploy. No build settings needed.

CONTACT

Phone: +256 746 200 441 / +256 762 093 951
WhatsApp: https://wa.me/256746200441
Email: samridahservices@gmail.com
Address: Mutungo 1 Zone 1A, Nakawa, Kampala, Uganda

TO DO

- Admin page for viewing orders
- Customer testimonials
- Photo gallery
- Mobile Money payment option

LICENSE

Copyright 2026 Samridah Cleaning Services. All rights reserved.
