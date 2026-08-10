# Energia EE PWA - TTF ja Elenger gaasihind

Uuendused:
- Gaasi kaart ei küsi enam Eleringi gaasi API-st andmeid.
- Kuvatakse eraldi TTF hind ja Elengeri kuupõhine paindliku paketi hind.
- Gaasihinnad on käsitsi muudetavad ja salvestatakse brauserisse.
- Elektrihinna graafikul on tooltip hiire/sõrmega andmepunktile liikudes.
- Kui tänased elektriandmed on localStorage'is olemas, ei tee leht avamisel uut API päringut.

Vaikimisi gaasihinnad:
- TTF: 53,60 €/MWh
- Elenger: 0,680 €/m³, august 2026
- Teisendus: 10,55 kWh/m³

Kui Elengeri järgmise kuu hind on avaldatud, muuda see lehel ja vajuta “Salvesta gaasihinnad”.

GitHub Pages:
Failid peavad olema repository juurkaustas: index.html, manifest.webmanifest, sw.js, README.md ja icons/.

Pärast üleslaadimist tee Ctrl+F5 või kustuta mobiilis saidi cache, sest service worker võib vana versiooni hoida.
