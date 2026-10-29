# Cvičení 6

**Klonování repozitáře:**
- Klávesa Windows + R -> cmd -> Enter
```
mkdir c:\SCZO_2026
cd C:\SCZO_2026
git clone https://cesta.ke.forked.git.repozitari
uv sync
```

**Úkol 1:**
- Zobrazte si jasovy profil hrany ulozene v promenne "img" na libovolnem radku
- Vytvorte 1. a 2. parcialni derivaci puvodniho obrazu a zobrazte je spolu s jasovymi profily


**Úkol 2:**
- Vyfiltrujte obraz ‘hrana.mat‘ pomoci vybraneho zostrujiciho operatoru
- Prozkoumejte funkci GetProfileWidth
- Overte funkcnost filtrace jak zobrazenim vyfiltrovanych obrazu a odpovidajicich jasovych profilu, tak vypoctenim a porovnanim sirek profilu hran
- Mente parametr K nebo alfa a pozorujte, jak se s vysledny obraz a jasove profily hrany meni
- Nactete obraz ‘MRI_brain.jpg’ a filtrujte jej pomoci Laplaceova operatoru. Zobrazte vyslednou aproximaci Laplacianu
- Zostrete obraz MRI s vyuzitim ziskaneho Laplacianu.

**Úkol 3:**
- Načtěte obraz ‘ugly_quidditch.jpg’
- Zobrazte si obraz spolu s jeho histogramem a spektrem
- Aplikutje na obraz vhodnou filtraci na odstranění přítomného šumu
- Na vyfiltrovaný obraz použijte vhodnou transformaci kontrastu
- Na vyfiltrovaný obraz po transformaci kontrastu použijte vhodný operátor a zvýrazněte hrany v obraze


**Závěr cvičení:**
```
git add .
git commit –m „message“
git push origin main
```