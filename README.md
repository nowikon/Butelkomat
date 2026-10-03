# ♻️ Butelkomat

Prosta aplikacja (PWA) do liczenia oddanych butelek i puszek oraz zaoszczędzonej kwoty.
Działa w całości w przeglądarce, dane zapisują się lokalnie na telefonie.

## Stawki

Zmienisz je w `index.html`, w tablicy `ITEMS` (pole `price`):

- butelka plastikowa: 0,50 zł
- puszka aluminiowa: 0,50 zł
- butelka szklana: 1 zł

## Wdrożenie na GitHub Pages

1. Załóż konto na https://github.com (jeśli go nie masz).
2. Kliknij **New repository**, nazwij je np. `butelkomat`, ustaw **Public**, kliknij **Create repository**.
3. Kliknij **uploading an existing file** i przeciągnij **zawartość** folderu (pliki `index.html`, `manifest.webmanifest`, `sw.js` oraz folder `icons`). Kliknij **Commit changes**.
4. Wejdź w **Settings → Pages**. W sekcji **Build and deployment** wybierz **Deploy from a branch**, gałąź **main** i folder **/ (root)**, kliknij **Save**.
5. Po 1–2 minutach strona będzie pod adresem `https://TWOJ-LOGIN.github.io/butelkomat/`.

## Instalacja na telefonie

- **iPhone (Safari):** Udostępnij → *Dodaj do ekranu początkowego*.
- **Android (Chrome):** menu ⋮ → *Zainstaluj aplikację* / *Dodaj do ekranu głównego*.

Zawsze otwieraj aplikację z tej samej przeglądarki, w której dodałeś skrót, bo dane są zapisane w jej pamięci.
