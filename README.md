# Pocket Cat

A pocket cat for Shay. One static page, no build step.

## Put it online with Cloudflare Pages
1. Cloudflare dashboard > Workers & Pages > Create > Pages > Connect to Git.
2. Pick this repo.
3. Framework preset: None. Build command: leave empty. Build output directory: `/` (or leave blank).
4. Save and Deploy. You get an address like `pocket-cat.pages.dev`.

## Put it on the tablet
1. Open the address in the tablet's browser (Safari on iPad, Chrome on Android).
2. Share menu (iPad) or the three dots menu (Android) > Add to Home Screen.
3. Always open the cat from that icon. The cat's progress is saved in that browser on that tablet.
   Clearing website data, private browsing or opening a different address starts a new kitten.

## Updating
Change `index.html`, commit, and Cloudflare redeploys. The tablet picks up the new version next time it is online.
