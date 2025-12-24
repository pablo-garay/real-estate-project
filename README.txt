https://realtechnologyinvestments.org
# Copyright (c) 2024.  All rights reserved.

================================================================================
REAL TECHNOLOGY - WEBSITE
================================================================================

This is a complete portable website, initially uploaded at :
https://realtechnologyinvestments.org

All pages have been downloaded with full content from the live site.

--------------------------------------------------------------------------------
FOLDER STRUCTURE
--------------------------------------------------------------------------------

website_workspace/
├── index.html              <- Homepage (FULL CONTENT)
├── assets/                 <- All CSS, JavaScript, and images
│   ├── *.css              <- Stylesheets
│   ├── *.js.download      <- JavaScript files
│   ├── *.png, *.jpg       <- Images
│   └── favicon-*.png      <- Favicons
├── about/index.html        <- About page (FULL CONTENT)
├── how-it-works/index.html <- How It Works page (FULL CONTENT)
├── reviews/index.html      <- Reviews page (FULL CONTENT)
├── faq/index.html          <- FAQ page (FULL CONTENT)
├── blog/index.html         <- Blog listing page (FULL CONTENT)
├── contact/index.html      <- Contact page (FULL CONTENT)
├── seller-form/index.html  <- Get Cash Offer form (FULL CONTENT)
├── privacy-policy/index.html <- Privacy Policy (FULL CONTENT)
├── terms-and-conditions/index.html <- Terms (FULL CONTENT)
└── README.txt              <- This file

--------------------------------------------------------------------------------
HOW TO USE OFFLINE
--------------------------------------------------------------------------------

1. Open index.html in any web browser
2. All navigation links work between pages
3. All styling and images work offline

Note: Form submissions will NOT work offline (they need a server backend)

--------------------------------------------------------------------------------
HOW TO DEPLOY TO A NEW DOMAIN
--------------------------------------------------------------------------------

1. Upload the entire website_workspace folder contents to your web server root
2. Make sure index.html is at the root of your domain
3. The site uses relative links, so it will work on any domain!

Example deployment:
   yourdomain.com/
   ├── index.html
   ├── assets/
   ├── about/
   ├── contact/
   └── ... (all other folders)

Access via:
   - Homepage: https://yourdomain.com/
   - About: https://yourdomain.com/about/
   - Contact: https://yourdomain.com/contact/

--------------------------------------------------------------------------------
MAKING FORMS WORK ON NEW DOMAIN
--------------------------------------------------------------------------------

The forms need a server-side handler. Options:

Option 1: Form Service (easiest)
   - Sign up for Formspree.io, Netlify Forms, or similar
   - Update form action attribute to your form endpoint

Option 2: PHP Backend
   - Create a PHP script to handle form submissions
   - Update form action to point to your script

Option 3: Connect to CRM
   - Integrate with your CRM (HubSpot, Salesforce, etc.)
   - Use their form embed or API

--------------------------------------------------------------------------------
NOTES
--------------------------------------------------------------------------------

- All content downloaded: December 2025
- Original site: https://realtechnologyinvestments.org/
- Some external URLs remain in meta tags (SEO/schema) - this is normal
- Popup and animation effects may have limited functionality offline

================================================================================
