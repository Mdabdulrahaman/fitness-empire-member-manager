FITNESS EMPIRE MEMBER MANAGER — GITHUB PAGES FILES

Files in this folder:
- index.html: the member-management app
- manifest.webmanifest: installable PWA metadata
- sw.js: offline app-shell service worker
- icon.svg, icon-192.png, icon-512.png: app icons

PUBLISH WITH GITHUB PAGES
1. Upload all six files to the ROOT of the repository (not inside another folder).
2. In the GitHub repository, open Settings > Pages.
3. Under Build and deployment, choose Deploy from a branch.
4. Choose branch main and folder /(root), then Save.
5. Wait for GitHub Pages to finish publishing. The site address should be:
   https://mdabdulrahaman.github.io/fitness-empire-member-manager/

IMPORTANT DATA NOTE
Member records are stored in the browser on each device. They are not uploaded to GitHub and are not automatically synced between iPhone and computer. Export a CSV backup before switching from the preview to the published site, then import it on the published site. Keep backups private.

SECURITY NOTE
This is currently a single-admin app with no login or cloud database. Do not treat the public website as a secure multi-user system. Anyone who can access the public site can open the app on their own device, but their local member records remain in their own browser.
\nUpdated branding: fitness-empire-logo.jpg is the supplied wide logo; app icons use the same artwork.\n