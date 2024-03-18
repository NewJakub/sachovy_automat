# FS šachový automat

- Autor: Jakub Černošek
- Verze 1.0
- Datum: 16.3.2024

## Úvod
### Účel
- Účel dokumentu je detailní popsání funkcí a stavů aplikace.
### Konvence dokumentu
- Hlavní nadpisy jsou označené jako "#". Podnadpisy jsou pak označené "##" a "###". Nížší úrovně jsou už označované "nestováním bullet listů" pomocí znaku "-". 
--------------------------------------------------------
### Pro koho je dokument určený
- Programátory, vývojář, designery a zákazníky.
### Odkazy na další dokumenty
- SRS šachový automat

## Scénáře

### Všechny reálné způsoby použití
- Způsob používání je jen jeden z důvodu jednoduchosti aplikace.

### Typy uživatelských rolí
- Hráč: Hráč může zapnout hru a ukončit aplikaci. Víc typů není potřeba.

### Vymezení rozsahu 
- V aplikace nebude možnost importovat hry ve formátu PGN, rozehranou hru uložit nepůjde.
- Také nebude možné si ze začátku rozestavit figurky - vždy se bude začínat ze základní pozice.

### Pracovní tok

- Zapnutí hry nebo vypnutí aplikace
  - Po zapnutí aplikace se uživateli zobrazí hlavní hlavní menu. Zde se budou nacházet dvě tlačítka, které budou umístěné uprostřed okna. Pomocí horního tlačítka zapneme novou hru. Pomocí spodního tlačítka aplikaci vypneme.

- Nastavení hry 
  - Když se uživatel rozhodne pro zapnutí hry, tak se mu ukáže nabídka ve které si bude moct vybrat barvu za kterou bude hrát a jestli bude zapnut časovač.

- Hra
  - Po dokončení nastavení se hráči zobrazí šachovnice, na které bude moct hrát proti šachovému automatu. Uživatel také bude moct pozastavit hru pomocí tlačítka v levém horním rohu nebo tlačítka "Esc". V tomto prostředí se bude nacházet dokud hra neskončí anebo aplikaci nevypne.
  - Pokud se hráč rozhodne hru pozastavit, tak se mu objeví okno, které bude obsahovat opustit hru a zpátky do hry.

- Konec hry
  - Když skončí hra, uživateli se zobrazí okno místo šachovnice. V tomto okně si bude moct vybrat, jestli chece hrát znovu nebo jestli chce aplikaci ukončit. 

### Hlavní moduly (samotné obrázky jsou jenom orientační, barvy budou dodělané podle vybraného schéma)
- Hlavní menu
  - Zde se budou nacházet dvě tlačítka ("Zapnout hru" a "Opustit aplikaci"), které budou umístěné uprostřed okna.  

- Nastavení hry
  - Bude obsahovat dvě dropdown menu ("Barva" a "Časovač") a jedno tlačítko (Zapnout hru).
- Okno pozastavení hry
  - Okno se bude skládat ze dvou tlačítek ("Vrátit se do hry" a "Opustit aplikaci"), které budou uprostřed obrazovky.  
- Šachovnice
  - Po dokončení nastavení se hráči zobrazí šachovnice, na které bude moct hrát proti šachovému automatu.

- Finální menu
  - Zde se budou nacházet dvě tlačítka ("Hrát znovu" a "Opustit aplikaci"), které budou umístěné uprostřed okna.
