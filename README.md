# Hardtimes-

This repository contains a minimal GitHub Pages site for CPV Hardtimes.

Live preview URLs

- GitHub Pages default URL (automatically after build):
  https://clint87vaughn-hash.github.io/Hardtimes-

- Custom domain (after DNS is pointed and GitHub Pages is configured):
  https://cpvhardtimes.com

What I added

- index.html — a minimal page that includes the Tawk.to chat widget.
- CNAME — contains `cpvhardtimes.com` so GitHub Pages knows about the custom domain.

DNS steps (you must do this with your domain registrar or DNS provider):

- For the apex domain (cpvhardtimes.com) add four A records pointing to GitHub Pages IPs:
  - 185.199.108.153
  - 185.199.109.153
  - 185.199.110.153
  - 185.199.111.153

- If you prefer to serve from a subdomain (e.g., www.cpvhardtimes.com), add a CNAME record pointing to:
  - clint87vaughn-hash.github.io

After you update DNS, visit https://cpvhardtimes.com (or the Pages URL) and allow a few minutes for GitHub to provision HTTPS and for DNS to propagate.

How to remove or change the chat widget

- Edit index.html in the repo, remove the Tawk.to <script> block, and commit the change.

If you want, I can also:
- Add a simple 404.html or other pages.
- Move the widget into a layout if you convert this to a Jekyll site.

