Persona Chat - installable app (PWA)

HOST IT (free, ~2 minutes)
  Netlify:  go to app.netlify.com/drop and drag this whole folder onto the page.
  GitHub Pages / Vercel / Cloudflare Pages also work: upload these files as-is.
  The site must be served over https (all of the above do this for you).

INSTALL IT
  Desktop (Chrome/Edge): open your site, click the install icon in the address bar.
  Android (Chrome): menu > Install app.
  iPhone/iPad (Safari): Share > Add to Home Screen.
  It then opens in its own window with the flame icon and works offline.

NOTES
  - Chats and characters are saved in that browser/app only (localStorage).
  - When you update index.html, change V="persona-chat-v1" in sw.js (e.g. v2)
    so installed copies pick up the new version.
