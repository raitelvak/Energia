# Energia EE PWA

Failid:
- index.html - äpi põhivaade
- manifest.webmanifest - PWA manifest
- sw.js - service worker offline/äpi cache jaoks
- icons/ - ikoonid

Kasutamine:
1. Laadi kogu kaust veebiserverisse, GitHub Pagesi, Netlifysse, Vercelisse või StackBlitzi.
2. Ava HTTPS aadress telefonis.
3. Android/Chrome: vajuta "Lisa äpp" või "Add to Home screen".
4. iPhone/Safari: Share -> Add to Home Screen.

NB! PWA installimine vajab tavaliselt HTTPS aadressi. Kohalikult failina avades võib leht töötada, kuid service worker ja installimine ei pruugi toimida.


## Parandused selles versioonis
- API päringutele lisatud CORS fallback.
- Lisa äpp nupp avab juhise, kui brauser automaatset PWA akent ei paku.
- GitHub Pages jaoks sobiv struktuur: failid peavad olema repository juurkaustas.
