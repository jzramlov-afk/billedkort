# Billedkort – musik med billeder

En enkel webapp til iPad: to store coverbilleder vises ad gangen. Ét tryk på et billede → en dansk stemme siger sangens titel → YouTube-videoen spiller på hele skærmen. Når sangen er slut, vises to nye, tilfældige billeder ud af fire.

- Sangene står i `SONGS` øverst i scriptet i `index.html` (titel + YouTube-id).
- Åbn via GitHub Pages: https://jzramlov-afk.github.io/billedkort/
- Appen starter med en tilfældig sang bag en "TRYK HER"-cirkel; sangen spiller færdig, derefter siger stemmen "Vælg en sang".
- Egne videofiler: Opstartsskærmen → "Indstillinger" → vælg en fil pr. sang. Filerne gemmes kun lokalt på iPad'en (IndexedDB) og afspilles uden reklamer. Sange uden fil afspilles fra YouTube.
