KABOOTAR JAA — LIVE WEBSITE PACKAGE
===================================

Included:
- Kabootarjaa.html — repaired production frontend
- assets/logo.webp — optimized Kabootar Jaa logo
- assets/kabootar-ja.mp3 — extracted music asset from the original HTML

WHAT WAS FIXED
---------------
1. Removed huge Base64 logo and music from the HTML.
2. Added proper meta description, Open Graph metadata and theme color.
3. Added responsive/mobile improvements and visible keyboard focus states.
4. Added form autocomplete, input limits and client-side validation.
5. Added order ID generation for every subscription request.
6. Added a hidden honeypot field to reduce simple spam submissions.
7. Improved Web3Forms order notification data.
8. Improved WhatsApp opening and added a visible fallback link if a browser blocks popups.
9. Fixed the broken/mis-encoded heart text in the submit button.
10. Kept the existing Kabootar Jaa plans, UPI ID, WhatsApp number, email address, pages and visual style.

HOW TO DEPLOY
--------------
Upload the entire folder contents to any static host while preserving:
  Kabootarjaa.html
  assets/logo.webp
  assets/kabootar-ja.mp3

Recommended options:
- Netlify
- Vercel
- GitHub Pages
- Cloudflare Pages
- Any normal cPanel/shared-hosting public_html folder

If the website should open at the domain root, rename Kabootarjaa.html to index.html before upload.

IMPORTANT CHECKS BEFORE GOING LIVE
----------------------------------
- Confirm the Web3Forms access key belongs to your own Web3Forms account.
- Confirm UPI ID: sanaghosh.1997@oksbi
- Confirm payee name: Sanirita Ghosh
- Confirm WhatsApp number: +91 8927463699
- Test all three plan QR amounts (₹299 / ₹799 / ₹1,999).
- Make one small real/test UPI payment and verify the UTR + WhatsApp/email flow.
- Test from Android Chrome, iPhone Safari and desktop Chrome.
- Add your final domain URL to your privacy/terms and social profiles if required.

PAYMENT ARCHITECTURE NOTE
-------------------------
This version remains a manual UPI-verification workflow, matching the original site:
customer pays by UPI -> enters UTR -> order notification is sent -> customer is directed to WhatsApp -> you verify payment manually.

It is NOT an automated payment gateway or recurring-card subscription system. For automatic payment verification, refunds, subscription renewals, customer accounts, order database and an admin dashboard, a backend + payment gateway integration is required.

SECURITY NOTE
-------------
The current static site uses Web3Forms from the browser. Do not treat a browser-ex
