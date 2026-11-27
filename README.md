# SEND IT! Used Dirt Bike Inspector

**Don't get burned on a used dirt bike.** SEND IT! is a pocket inspector for buying a used dirt bike. It walks you through 38 checks a mechanic would make, plus extra checks for motocross, trail, dual-sport and enduro bikes. It flags the dealbreakers and gives you a straight answer: **send it, negotiate or walk away.** It also keeps every bike, seller and appointment in one place while you shop.

**Open the app:** https://ajdrozd-ux.github.io/send-it-inspector/

## How it works
1. **Add the bike.** Tap *Start New Inspection* and enter the make and model. The app detects the bike type and adds the right checks. Add the listing link, seller, asking price and appointment.
2. **Check the VIN.** Type the VIN from the steering head to confirm the maker and model year.
3. **Go through the checklist.** Mark each item Good, Issue or Skip. Dealbreaker items are flagged.
4. **Get the verdict.** See the score, every problem found and a clear call.
5. **Know what it's worth.** Each bike shows an estimated market value from its year, engine size, brand, hours and inspection results, and tells you if the asking price is high. Repair costs typed into issue notes ("$180 fork seals") come off the value. Tap *eBay sold* or *Marketplace* for real prices, or enter a J.D. Power number as *Book value*.
6. **Negotiate and share.** Use the problem list to back up your offer, and tap *Share report* to send the results.
7. **Keep track.** Follow each bike from Watching to Bought or Passed, rate sellers, and plan a multi-stop route in Google Maps.

## What the verdict means
| Verdict | When |
|---|---|
| **Send it** | 85%+ of checks good and no dealbreakers |
| **Negotiate** | 65–84% good |
| **Walk away** | Any dealbreaker, or under 65% good |

At least half the list has to be checked before a verdict appears. Skipped items don't count against the bike.

## Put it on your home screen
- **iPhone:** open the link in Safari → Share → *Add to Home Screen*
- **Android:** open it in Chrome → ⋮ menu → *Install app*

Once installed it opens full screen and works with no signal.

## Your data
Everything stays on your phone. There's no account and nothing is uploaded. Clearing your browser data or deleting the app removes your inspections.

---

### For developers
- `index.html` – the whole app (vanilla JS, no build step)
- `manifest.webmanifest`, `icons/` – install name and home-screen icons
- `sw.js` – offline cache. Bump `CACHE` when releasing changes so installed phones update.
