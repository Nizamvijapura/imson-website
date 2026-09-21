IMSON™ WEBSITE — GITHUB PAGES

Files included:
- index.html              Home
- products.html           Products (live Supabase data)
- about.html              About Us
- contact.html            Contact
- toner-finder.html       Existing live Supabase Toner Finder + Owner Update
- qr-verification.html    Existing live Supabase QR verification + Owner Panel
- styles.css              Common website theme/header
- assets/imson-logo.jpg   FINAL IMSON logo supplied by owner
- CNAME                   www.imson.co.in

IMPORTANT:
The Toner Finder and QR Verification pages keep the existing Supabase project/database configuration and table names:
- toners
- qr_products
The existing Supabase publishable key is retained in the HTML files exactly as used by the working pages.

GITHUB PAGES:
1. Open the GitHub repository used for the IMSON website.
2. Upload all files/folders from this package to the repository root.
3. Commit the changes to the main branch.
4. Settings → Pages → Source: Deploy from a branch → main → / (root).
5. Custom domain: www.imson.co.in
6. Wait for DNS/TLS to finish. Enable Enforce HTTPS after GitHub shows it is available.

The CNAME file is already included for www.imson.co.in.

QR LINKS:
A product QR can continue to use:
https://www.imson.co.in/qr-verification.html?qr=255
Replace 255 with the QR code stored in qr_products.

SUPABASE:
No database tables, records, credentials, or schema are changed by these website files.
