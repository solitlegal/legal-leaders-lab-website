LEGAL LEADERS LAB WEBSITE: DEPLOYMENT NOTES

Upload the contents of this folder to the root of your web host.

BEFORE GOING LIVE, REPLACE THESE PLACEHOLDERS
1. Domain: https://www.legalleaderslab.be/ appears in index.html (canonical, social
   tags, structured data), robots.txt and sitemap.xml. Search and replace it with
   your real domain.
2. Email addresses: hello@legalleaderslab.be and community@legalleaderslab.be.

AFTER GOING LIVE
1. Add the site to Google Search Console and Bing Webmaster Tools, verify the
   domain and submit sitemap.xml.
2. Turn on HTTPS, gzip or brotli compression and long cache headers for /fonts
   and images (most hosts such as Netlify, Vercel or Cloudflare Pages do this).
3. Check the share preview with the LinkedIn Post Inspector
   (linkedin.com/post-inspector).

WHAT IS INCLUDED
index.html            The website with full SEO metadata and structured data
fonts/                Self-hosted fonts (SIL Open Font License), no Google requests
og-image.png          Share image for LinkedIn and other platforms (1200 x 630)
favicon.ico/.svg      Browser icons; apple-touch-icon.png and icon-*.png for devices
site.webmanifest      App manifest
robots.txt, sitemap.xml  Search engine files
