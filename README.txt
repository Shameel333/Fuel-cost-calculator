Trip Fuel Cost: installable app

Files
  index.html            the app
  manifest.webmanifest  name, colours and icons used when installing
  sw.js                 lets the app open offline
  icons/                app icons

Put it online (needs HTTPS, which these hosts give you)
  Netlify Drop:  open app.netlify.com/drop and drag this whole folder onto the page.
  GitHub Pages:  upload these files to a repo, then Settings > Pages > deploy from the main branch.

Install on your phone
  Android (Chrome):  open the site, menu > Install app.
  iPhone (Safari):   open the site, Share > Add to Home Screen.

After you change any file, change CACHE in sw.js (for example fuel-cost-v2)
so phones pick up the new version.
