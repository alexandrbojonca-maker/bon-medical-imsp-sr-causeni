FIX IMPORTANT

Problema găsită:
- În bon_integrat_farmacia.html exista o eroare JavaScript: MANUAL_CATALOG era declarat de 2 ori.
- Din cauza asta se oprea tot scriptul și Google Sheets sync nu putea funcționa.
- Importul CSV a fost ajustat ca să citească și structura farmaciei:
  item_id, denumire, total_valoare, cantitate, pret_unitar, moneda, validare...

Ce trebuie încărcat pe GitHub:
1. bon_integrat_farmacia.html
2. index.html
3. db.js
4. farmacia_data.js
5. prices.js
6. farmacia_export.csv
7. restul fișierelor README/CSV, dacă doriți

După upload pe GitHub:
- deschideți:
  https://alexandrbojonca-maker.github.io/bon-medical-imsp-sr-causeni/
- lipiți CSV linkul publicat din Google Sheets
- apăsați Conectează

Dacă nu merge:
- apăsați F12 → Console și copiați eroarea.
