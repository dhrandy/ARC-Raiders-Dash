# ARC Raiders Dash

Tactical loadout optimizer for [ARC Raiders](https://www.arcraiders.com) by Embark Studios. Track weapons, manage your arsenal, and plan your raids.

**Live:** https://dhrandy.github.io/ARC-Raiders-Dash/

## What it does

- **Weapons** - Browse all 26 weapons with stats, firing modes, ammo types, and PvE/PvP breakdowns. Filter by category or ammo type, search, and mark what you own.
- **Grenades & Throwables** - Full list of grenades and scavenged throwables with damage, radius, and best-use tips.
- **Battleground Intel** - Map guides for all 7 zones (Dam Battlegrounds, Spaceport, Buried City, The Blue Gate, Stella Montis, Pendola Pass, Riven Tides) with loot spots, ARC spawns, extraction points, and tips.
- **Loot Focus List** - Track what you're farming.
- **Arsenal Management** - Select the weapons you own; the dash filters everything else to match.

Your picks, notes, and favorites are saved in the browser (localStorage). No account, no backend.

## How to use

1. **Open the dash** at the live link above (or open `ARC-Raiders-Dash.html` locally).
2. **Weapons tab** - Browse the arsenal. Use the category buttons (assault rifles, SMGs, shotguns, etc.) or the ammo filter to narrow it down. Click a weapon for full stats, pros/cons, and PvE/PvP notes.
3. **Arsenal Management** (hamburger menu, top right) - Check off the weapons you actually own. The dash filters everything else to match your inventory, so you're only comparing what you can bring.
4. **Loot Focus List** - Add items you're farming so you know what to grab topside.
5. **Grenades tab** - Look up any grenade or throwable before a raid.
6. **Battleground Intel tab** - Pick your map for loot locations, ARC spawns, extraction points, and tips.

Tip: install it as an app from your browser's menu for fullscreen offline use.

## Run it

It's a single HTML file. Open `ARC-Raiders-Dash.html` in any browser, or host it anywhere static.

It ships as a PWA (`manifest.json` + `service-worker.js`), so it installs and works offline once loaded.

## Data

Weapon, grenade, and map data is hand-maintained and current through the **Frozen Trail 2.0** update (Oct 2026). Embark rebalances regularly, so treat numeric stats as approximate.

## License

Fan project. ARC Raiders is a trademark of Embark Studios.
