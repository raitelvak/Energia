# Energia EE Daily PWA + tasud

Uuendused:
- Näitab börsihinda s/kWh.
- Näitab hinnangulist lõpphinda koos tasudega.
- Tasude seadistuses saab muuta võrgutasu ja müüja marginaali.
- Graafikut saab vaadata kas börsihinna või lõpphinnana.
- Andmete päring toimub 1x päevas ja tulemus salvestatakse brauserisse.

Vaikimisi tasud:
- Võrgutasu: 6,000 s/kWh, näidisväärtus, muuda oma paketi järgi.
- Müüja marginaal: 0,200 s/kWh.
- Taastuvenergia tasu: 0,840 s/kWh.
- Varustuskindluse tasu: 0,758 s/kWh.
- Tasakaalustamisvõimsuse tasu: 0,373 s/kWh.
- Elektriaktsiis: 0,100 s/kWh.
- Käibemaks: 24%.

GitHub Pages:
Failid peavad olema repository juurkaustas: index.html, manifest.webmanifest, sw.js, README.md ja icons/.

Pärast üleslaadimist tee Ctrl+F5 või kustuta mobiilis saidi cache, sest service worker võib vana versiooni hoida.
