TenderFit - static site, no build step, no server, no external requests.

Deploy:
  Netlify / Cloudflare Pages / Vercel: drag-and-drop this folder.
  GitHub Pages: push the folder, enable Pages.
  Any web host: upload index.html.
  Local: double-click index.html.

How it avoids made-up output:
  - Requirements are the tender's own sentences, shown as written.
  - Statuses come from fixed rules comparing tender numbers/certificate names to your saved profile.
  - Anything not clearly matched is marked "Review", never "Met".
  - Draft text only repeats your profile data and the tender's wording.
Data stays in the visitor's browser (localStorage).
