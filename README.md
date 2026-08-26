# Energia EE, GitHub Actions versioon

Elektrihinnad laadib GitHub Actions iga päev faili `data/prices.json`. Veebibrauser ei tee enam päringut NordAPI-sse, mistõttu CORS-i `Failed to fetch` viga kaob.

## Seadistamine
1. Laadi kõik selle paketi failid GitHubi repository juurkausta.
2. Veendu, et üles läksid ka `.github/workflows/update-prices.yml` ja `data/prices.json`.
3. Ava GitHubis `Settings > Actions > General`.
4. Vali `Workflow permissions > Read and write permissions` ja salvesta.
5. Ava `Actions > Update electricity prices > Run workflow`.
6. Oota rohelist linnukest. Seejärel kontrolli faili `data/prices.json`.
7. Oota GitHub Pagesi uut deploy'd ning tee lehel `Ctrl + Shift + R`.

Töövoog jookseb iga päev kell 13:15 UTC, mis on Eesti suveajal 16:15.
