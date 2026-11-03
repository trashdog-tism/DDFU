# Dog's Dungeon Fucker Upper

Hit the button, get a modifier, run the dungeon with it.

## Modifiers
- Double Primary
- No Exotics
- Only use weapons you have no kills on
- Triple Shotgun
- Muzz picks your Exotic Weapon
- Ty picks your subclass
- RanDIM Loadout
- Copy Ty's Loadout
- Use the build randomiser

Untick any modifier to pull it from the pool (remembered per device). It never rolls the same one twice in a row.

## Hosting on GitHub Pages
1. Create a new repo and upload everything in this folder (keep the `icons` folder).
2. Repo **Settings → Pages** → Source: *Deploy from a branch*, Branch: `main` / `(root)` → Save.
3. It'll be live at `https://<your-username>.github.io/<repo-name>/` in a minute or so.

## Editing
- Modifiers live in the `MODIFIERS` list near the bottom of `index.html`.
- To make "Use the build randomiser" open your randomiser, paste its URL into the `link: ""` on that line.
- After changing files, bump `CACHE = "ddfu-v1"` in `sw.js` (e.g. to `v2`) so installed copies refresh.

## Android install
It's a PWA, so you can either "Add to Home screen" from Chrome, or run the Pages URL through PWABuilder for an APK.
