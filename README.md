# 44. sz. Zrínyi Miklós Cserkészcsapat honlapja

Élő oldal: https://44zrinyi.vercel.app/

## Szerkesztés

A honlap fájljai itt, ebben a repóban vannak. Ha szerkesztesz egy fájlt a
github.com-on, a mentés után a Vercel 1-2 percen belül automatikusan kiadja
az oldalt — nem kell külön deploy-olni.

Egyszerű szövegjavítás: nyisd meg a fájlt (pl. `szuloknek.html`), kattints
a ceruza ikonra, írd át, majd "Commit changes".

## Kivételek — ezeket ne szerkeszd kézzel

- `foglalkozasok.html` (Naptár): havonta újragenerálódik a csapat
  Google-naptárából, a kézi szerkesztés felülíródik.
- A bejgli sütés táblázata (`szuloknek.html`-ben) élőben a Google
  Sheetből jön.

## Technikai tudnivalók

- Statikus oldal, nincs build lépés. A `vercel.json` a képek
  gyorsítótárazását állítja be.
- Vercel projekt: `brisk-monsoon-5qhoao3` (44-esek csapat).
  Production branch: `main`.
