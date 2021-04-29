# Procesas

- [x] pradine failu struktura:
    - index.html
    - .gitignore
    - main.css (bet ne butinai vienintelis)
- [x] Paviesinti projekta per Github Pages (gausim URL)
- [x] Readme.md
    - skirta aprasyti kas, ka ir kodel daro
    - iterpti nuoroda i daroma dizinai
    - iterpti nuoroda, kur tas musu kodas gali buti pamatytas
- [x] atlikti dizaino analize
- [x] surasyti HTML
- [x] issikirpti nuotraukas ir jas panaudoti:
    - panaudoti reliatyvu kelia
- [x] aprasome stiliu:
    -turinys turi buti centre (tiek horizontaliai, tiek vertikaliai)
    - pagrindinis plotis turi buti fiksuotas
 - [] atskiri puslapiai, kurie naviguoja "ratu"
    - sign up
    - sign in
    - forgot password
- [] css turi buti tik vienas failas, kur stiliaus taisykles veikia vienodai (identiskai) per visus puslapius.   

# Pozicionavimas

1. Vaikui duodam `position: absolute`;
2. Artimiausiam logiskai teviniam elementui, kuri norime tureti kaip atskaitos taska, suteikiame:
    a) `position: relative`, jeigu tas elementas neturi kitokiu `position` savybiu;
    b) paliekame tokia `position` savybe kokia tas elementas turi, jei nurodytas;

Isvada:
absoliuciai pozicionuojamas elementas bus pastatytas artimiausio ne `position: static` elemento atzvilgiu.