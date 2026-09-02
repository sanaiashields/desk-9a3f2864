# The Desk — install as an app

This folder is a small installable web app: your calendar, assignments,
inbox, and notepad in one page. To install it on your phone or computer,
it needs to be served from a real web address first (installing straight
from a file on your computer doesn't work in most browsers).

## Fastest way — Netlify Drop (no account needed)

1. Go to **app.netlify.com/drop**
2. Drag this whole folder (all 5 files — `index.html`, `manifest.json`,
   `sw.js`, and the two icon PNGs) onto the page
3. Netlify gives you a live URL in a few seconds
4. Open that URL on your phone

## Free option with an account — GitHub Pages

1. Create a free GitHub account if you don't have one
2. Create a new repository and upload these 5 files to it
3. In the repo, go to **Settings → Pages**, and set the source to your
   main branch
4. GitHub gives you a URL like `yourname.github.io/reponame`

## Installing it once it's online

- **iPhone (Safari):** open the URL → tap the Share icon → **Add to
  Home Screen**
- **Android (Chrome):** open the URL → tap the menu (⋮) → **Install app**
  (or you'll see an "Install app" button appear in the page itself)
- **Desktop (Chrome/Edge):** open the URL → click the install icon in the
  address bar, or use the "Install app" button in the page

Once installed, it opens in its own window with its own icon — no browser
bar, and it still works offline since it caches itself the first time you
open it.

## Editing your data

Open `index.html` in any text editor and look for the `classes`,
`seedAssignments`, and `seedMail` objects near the bottom — that's your
sample schedule, assignments, and inbox. Replace them with your own.
