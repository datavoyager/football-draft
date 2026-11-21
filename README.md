# All-Time Football Draft Tracker PWA

## What it does
- Tracks Luke, Jon, Tom, Mark and Jeff
- £500m budget per team
- Records player/manager, price, round and genuine positions
- Autosaves locally on the device
- Shows spending, balance, legal maximum next bid and formation possibilities
- Exports/imports a JSON backup
- Works offline after first successful load

## Important: how to install
A PWA must be served over HTTPS (or localhost). Opening index.html directly from the Files app will not provide full installation/service-worker behaviour.

### Easiest hosting options
1. GitHub Pages: upload these files to a repository, enable Pages for the branch, then open the HTTPS Pages address on the phone.
2. Azure Static Web Apps: deploy this folder as a static site.
3. Netlify Drop / Cloudflare Pages: deploy the folder and use the supplied HTTPS address.

### Install on iPhone
Open the HTTPS site in Safari, tap Share, then Add to Home Screen.

### Install on Android
Open the HTTPS site in Chrome or Edge, open the browser menu, then tap Install app or Add to Home screen.

## Data safety
Draft data is stored only in that browser profile on that device. Use Export after every few rounds. Clearing site data or deleting the app can remove local data. Import restores a saved JSON backup.

## Cheat sheet v2
- Includes the top 50 cheat-sheet players in overall rank order.
- Search/filter by position.
- Tap Buy to pre-fill a purchase.
- Once the purchase is saved, that player automatically shows SOLD with team, price and round.
- If a purchase is deleted, the player becomes AVAILABLE again.

## v3: non-cheat-sheet players
The blue + Any purchase button is always available. Enter any player or manager name manually, select all genuine positions, team, round and price. Cheat-sheet players continue to update to SOLD automatically when their names match.
