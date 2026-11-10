# Adobe MAX 2026 prehľad

Interaktívny prehľad noviniek z konferencie Adobe MAX 2026 (Miami Beach, 10.–12. 11. 2026): novinky s filtrom podľa oblasti a stavu, videá prehrávané priamo na stránke, príspevky zo sociálnych sietí, program a zdroje.

**Živá stránka:** https://yalkster.github.io/adobemax2026/

## Ako to funguje

- Celá stránka je jeden súbor `index.html`, bez build kroku a bez závislostí.
- Hosting cez GitHub Pages z vetvy `main`, priečinok `/`.
- Videá sa prehrávajú cez vložený prehrávač YouTube. Funguje to na webe (https). Pri otvorení súboru dvojklikom z disku môže YouTube prehrávač odmietnuť.
- Zábery a krátke ukážky pri novinkách sa načítavajú priamo z blogu Adobe (blog.adobe.com, video.tv.adobe.com). Ak ich Adobe presunie, karta sa zobrazí bez obrázka.
- Označenie „prečítané“ sa ukladá len v prehliadači návštevníka.

## Úprava obsahu

Obsah je v `index.html` v poliach `NEWS`, `VIDS`, `SOCIAL` a `EVENTS`. Po úprave stačí commit do `main`.

Neoficiálny prehľad zostavený z tlačových správ Adobe a článkov médií. Stav k 10. 11. 2026.
