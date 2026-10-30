# Digitális EC2 vasbeton segédlet – v2.3

Statikus Vercel-kompatibilis alkalmazás. A 76 oldalas PDF a `assets/vasbeton-segedlet.pdf` fájlban, az automatikusan kinyert szövegindex a `data/pages.json` fájlban található. A PDF állandóan online, nem kell kézzel feltölteni a megnyitásakor.

## Telepítés

A ZIP **tartalmát** töltsd a GitHub repository gyökerébe, a jelenlegi `index.html` és PDF frissítésével. Vercel: Framework Preset = Other, Build Command üres, Output Directory üres (root).

## Funkciók

- Fejezetjegyzék és az eredeti PDF közvetlen megnyitása
- Oldalankénti szövegkeresés, találati előnézet és PDF-oldalra ugrás
- Beton- és betonacél-táblázatok, egyszeresen vasalt téglalap hajlítási prototípus

**Korlát:** az index automatizált szövegkinyerésből származik, sok oldalon elforgatott vagy hibás. Képletellenőrzésre nem használható. A dokumentum nyilvános megosztásához a felhasználási jogokat tisztázni kell.
