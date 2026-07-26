# Feedback log

Notes from Charlie, sent from the app's 💬 button (share sheet / email to Daddy), logged and tracked here.

| Date | Note | Context | Status |
|---|---|---|---|
| 2026-07-22 | Photos aren't displayed properly | v5 · looking at Apistogramma cacatuoides | ✅ Fixed in v6 — lookup now uses exact Wikipedia titles first, not search |
| 2026-07-22 | The otocinclus photo is set as a cat | v5 · looking at Otocinclus | ✅ Fixed in v6 — same fix; photo cache purged, cat evicted 🐱→🐟 |
| 2026-07-22 | Need to change the type of shrimp (Caridina typus / Australian amano) | v5 | ✅ Done in v6 — shrimp-type selector in Current crew; amano-types get their own temps and no shrimplet warnings (they can't breed in freshwater) |
| 2026-07-22 | Add fish to the "current crew" menu | v5 · looking at German Blue Ram | ✅ Done in v6 — add fish you own as crew chips; every diagnosis checks shared temperature windows with them; temperament pairings honestly flagged as "not in my data — cross-check" |
| 2026-07-22 | Apistogramma cacatuoides is set so it thinks you need a pair | v5 | ✅ Fixed in v6 — now "1 male, pair, or harem", with single-male noted as the easy mode. Good catch — you were right |
| 2026-07-23 | When you open a fish page, the images are just displayed as a thin strip | v7 · looking at Apistogramma cacatuoides | ✅ Fixed in v8 — the detail photo was a fixed 128px band at full width (7:1 on a big screen), so `cover` cropped it to a letterbox strip. Now a centred 3:2 photo card that scales, showing the *whole* fish (no cropped tails) |
| 2026-07-24 | Add water parameters (GH, KH, pH) to the tank tab so conflict isn't only temperature and predation | v8 · looking at German Blue Ram | ✅ Done in v10 — pH/GH/KH inputs, per-species pH and GH ranges on all 16 fish, chemistry rows in every diagnosis, and the big one: soft-water fish now collide with the mystery snail's shell (a real conflict the app was blind to) |
| 2026-07-24 | A stocking section: planned fish, quantities, filtration, planting density, tank size → % stocked by bioload, adult size, swimming levels | v8 · looking at German Blue Ram | ✅ Done in v10 — new 📊 Stocking tab with a gauge, swimming-level split, group-size/solo/tank-size warnings, and the full workings shown (deliberately: there is no agreed stocking formula, so the model argues its own case) |
| 2026-07-24 | Pasting the "research with an AI" JSON says it isn't JSON | v8 · looking at German Blue Ram | ✅ Fixed in v10 — the reader now copes with iPad smart quotes, prose around the answer, code fences and trailing commas; if it still can't read it, it says what it actually saw |

