# Politike privatnosti

Javne stranice sa politikama privatnosti aplikacija za zakazivanje koje objavljuje NMS Solutions.
Objavljuju se preko GitHub Pages, sa grane `main`, iz korenskog foldera.

| Aplikacija | Adresa |
|---|---|
| Salon Igor | https://mosaicors.github.io/privatnost/salon-igor/ |

Početna strana (`index.html`) samo nabraja aplikacije. Svaka aplikacija ima svoj folder sa jednim
`index.html`: običan HTML bez skripti, spoljnih fontova i kolačića, čitljiv na telefonu i u tamnom režimu.

## Nov salon

1. Iskopiraj folder `salon-igor` pod novim imenom, na primer `salon-x`.
2. U novom `index.html` promeni samo podatke o salonu: `<title>`, ime aplikacije u zaglavlju (`<p class="lead">`),
   odeljak **1. Ko smo i kako da nas kontaktirate** (ime salona, adresa, telefon, mejl) i ime paketa u podnožju.
   Ostatak teksta govori o „salonu“ i „aplikaciji“, pa ne traži izmene dok aplikacija radi isto.
3. Promeni datum u zaglavlju („Važi od …“) i dodaj red u **Istoriju izmena** na dnu.
4. Dodaj karticu za novi salon u korenski `index.html`.
5. Commit i push na `main`. GitHub Pages objavi izmenu za minut ili dva.

Kad se promeni ono što aplikacija radi sa podacima (obaveštenja na telefon, prijava Google, Apple ili email
nalogom, prijavljivanje grešaka, rok brisanja starih termina), prvo se dopunjuje politika, sa novim datumom.

U ovaj repozitorijum ide samo ovo: nikakvi ključevi, podešavanja ni drugi fajlovi aplikacije.
