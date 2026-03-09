# BelaBlok 🃏

Web aplikacija za praćenje bodova u beli za **3 igrača**. Radi kao single HTML file, bez instalacije, optimizirana za mobitel.

## Kako koristiti

Otvori `bela-blok.html` u browseru — ništa drugo nije potrebno.

## Funkcionalnosti

- Unos imena igrača i odabir limita bodova (501 / 701 / 1001)
- Automatska rotacija tko zove (1→2→3→1...)
- Unos bodova po rundi s auto-popunjavanjem trećeg igrača (zbroj mora biti 162)
- Zvanja po igraču (+20, +50, +100, +150, +200)
- Pravila bodovanja:
  - Zvač prolazi ako mu je zbroj bodova + zvanja veći od oba protivnika
  - Ako zvač ne prođe, njegovi bodovi idu protivniku s više bodova, a zvač dobiva 0
- Uređivanje bilo koje prethodne runde
- Poništavanje zadnje runde
- Prikaz pobjednika kad netko dostigne limit

## Tech

Vanilla HTML/CSS/JS — jedna datoteka, nema dependencija, nema builda.