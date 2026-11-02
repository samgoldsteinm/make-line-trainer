# Make Line Trainer

A practice game for the make line. Build specialty pizzas, BYO order tickets, sandwiches, loaded chicken, pasta and Stuffed Cheesy Bread, and get graded on ingredients, portions and build order.

## Sections

- **Build** – pick an item and size, add ingredients in order, choose portions, then grade the build.
- **Timed Rush** – random builds against a 2, 3 or 5 minute clock.
- **Portion Drill** – quick multiple-choice questions on the topping, sauce, cheese, Pan, NY, bread and pasta charts.
- **Study Cards** – every build card and BYO chart.
- **Missed Review** – retest anything you scored under 100%.

## Install on your phone

Open the site, then:

- **iPhone (Safari):** Share → Add to Home Screen.
- **Android (Chrome):** menu → Install app (or Add to Home screen).

It works offline after the first visit. Scores save on each phone.

## Updating builds

All build data lives in `index.html` (`ITEMS` for the build cards, `TOPS` / `ALLPZ` / `STD_SAUCE` / `HT_CHEESE` / `PAN` / `NY` for the BYO charts). After changing it, bump `VERSION` in `sw.js` so installed phones pick up the update.
