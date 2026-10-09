Samridah Cleaning Services

Website for Samridah Cleaning Services, a cleaning company based in Kampala, Uganda.

Live site: https://samridah-website.vercel.app

WHAT IT DOES

The site shows the company's services, displays a live photo gallery, shows brief popup ads, and lets clients place orders through a form. Orders are sent by email to samridahservices@gmail.com via Formspree, and are also stored so they appear in the admin dashboard.

An admin panel lets the owner manage ads, photos, and view incoming orders without touching code.

SERVICES LISTED

- Residential cleaning (house cleaning, deep cleaning, carpets, windows)
- Commercial cleaning (offices, warehouses, malls, schools, hotels)
- Compound cleaning (sweeping, trimming, lawn mowing, designing)
- Other services (tile cleaning, detergents, air fresheners, toilet supplies)

FILES

- index.html - the public website
- admin.html - the admin dashboard (password protected)
- README.md - this file

HOW IT WORKS

Order form:
The form posts to Formspree, which emails the submission to samridahservices@gmail.com. After the email sends, the order is also saved to the database so it appears in the admin dashboard's Orders tab.

Admin panel:
Available at /admin.html. Password protected. From here the owner can:
- Add, edit, and delete ads shown on the public site
- Add, edit, and delete gallery photos
- View, contact, and remove incoming orders

Ads and photos:
Stored in a JSONBin.io bin. The main site reads from this bin on page load and refreshes every 60 seconds, so changes made in the admin panel appear on the public site automatically.

Images:
Uploaded to imgbb.com or postimages.org. Only the direct image link (ending in .jpg or .png) is pasted into the admin panel. The site does not host images itself.

ENDPOINTS AND KEYS

Formspree endpoint (in index.html):
https://formspree.io/f/mjygwnny

JSONBin bin ID (in both index.html and admin.html):
6ac91135ac6210605a2312fd

Admin password (in admin.html):
Change ADMIN_PASSWORD to something private before sharing the admin URL.

DEPLOYMENT

Hosted on Vercel. Every push to the main branch deploys automatically. No build step required - it is a static site.

To deploy manually: import the repo at vercel.com/new and click Deploy.

CONTACT

Phone: +256 746 200 441 / +256 762 093 951
WhatsApp: https://wa.me/256746200441
Email: samridahservices@gmail.com
Address: Mutungo 1 Zone 1A, Nakawa, Kampala, Uganda

TO DO

- Customer testimonials
- Mobile Money payment option
- Swap JSONBin for a database with proper authentication
- Verify custom domain

LICENSE

Copyright 2026 Samridah Cleaning Services. All rights reserved.
