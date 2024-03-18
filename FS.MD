# FS šachový automat

- Autor: Jakub Černošek
- Verze 1.0
- Datum: 16.3.2024

# Úvod
### Účel
- Účel dokumentu je detailní popsání funkcí a stavů aplikace.
### Konvence dokumentu
- Hlavní nadpisy jsou označené jako "#". Pod nadpisy jsou pak označené "###". Nížší úrovně jsou už označované "nestováním bullet listů" pomocí znaku "-". 
--------------------------------------------------------
### Pro koho je dokument určený
- Programátory, vývojář, designery a zákazníky.
### Odkazy na další dokumenty
- SRS šachový automat

# Scénáře

### Všechny reálné způsoby použití
- Způsob používání je jen jeden. 

### Typy uživatelských rolí
- Hráč: Hráč může zapnout hru a ukončit aplikaci. Víc typů není potřeba.

### Vymezení rozsahu 
- V aplikace nebude možnost importovat hry ve formátu PGN.
- Také nebude možné si ze začátku rozestavit figurky - vždy se bude začínat ze základní pozice.

### Na co se NEbude klást důraz (výkonnost)

# Celková hrubá architektura

### Pracovní tok
- 
### Hlavní moduly (samotné obrázky jsou jenom orientační, barvy budou dodělané podle vybraného schéma)
- Hlavní menu
  - Po zapnutí aplikace se uživateli zobrazí hlavní hlavní menu. Zde se budou nacházet dvě tlačítka, které budou umístěné uprostřed okna, jak jde vidět na obrázku. Pomocí horního tlačítka spustíme funkci funkce jmeno======== , která zapne novou hru. Pomocí spodního tlačítka spustíme funkci xxxxxxxx, která aplikaci vypne. 
![](https://github.com/NewJakub/sachovy_automat/blob/main/Screenshot%202024-03-18%20211953.png)
- Nastavení hry
  - Když se uživatel rozhodne pro zapnutí hry, tak se mu ukáže nabídka ve které si bude moct vybrat barvu za kterou bude hrát a jestli bude zapnut časovač.
- Šachovnice
  - Po dokončení nastavení se hráči zobrazí šachovnice, na které bude moct hrát proti šachovému automatu.
- Finální menu
  - Když skončí hra, uživateli se zobrazí okno místo šachovnice. V tomto okně si bude moct vybrat, jestli chece hrát znovu nebo jestli chce aplikaci ukončit. 
