# ODRUCH

**[Zagraj w przeglądarce](https://apkmason.dev/odruch/)**

Autorska platformówka 2D: 21 krótkich poziomów, trzy rozdziały i świat, który reaguje na ruch gracza. Precyzyjne skoki, przewrotne przeszkody i błyskawiczna kolejna próba.

Nie każda podłoga zostaje na swoim miejscu. Wybrane fragmenty rozsuwają się po zbliżeniu albo opadają po lądowaniu. Ich położenie i zachowanie są stałe, a odkryte miejsce pozostaje delikatnie oznaczone podczas kolejnych prób tej samej planszy. Restart po śmierci trwa około 0,32 sekundy.

## Sterowanie

| Akcja | Klawisze |
| --- | --- |
| Ruch | ← / → lub A / D |
| Skok | Spacja, W lub ↑ |
| Restart | R |
| Pauza | Esc |
| Wyciszenie | M |

Na telefonie dostępne są przyciski ekranowe. Ustawienia pozwalają osobno regulować muzykę i efekty oraz ograniczyć ruch dekoracji.

Postęp, rekordy i ustawienia są zapisywane lokalnie w przeglądarce. Nie są synchronizowane między urządzeniami. Dźwięk uruchamia się po interakcji z grą.

## Zawartość wydania

- **index.html** — wejście do gry w głównym adresie witryny.
- **dist/** — kompletna dystrybucja: strona gry, zminimalizowane pliki JavaScript i CSS, ikona i trzy gotowe nagrania MP3.
- **.nojekyll** — obsługa statycznych plików przez GitHub Pages.

Gra nie wymaga backendu, instalacji zależności ani zewnętrznych CDN. Do uruchomienia na innym hostingu wystarczy udostępnić zawartość katalogu **dist/** przez HTTP/HTTPS. GitHub Pages publikuje gałąź **main** z katalogu głównego.

To repozytorium zawiera wyłącznie gotowe wydanie. Narzędzia deweloperskie, testy, dokumentacja robocza i oryginalne materiały audio nie są częścią publikacji.

Poprzedni pakiet uruchomieniowy może pozostać w dystrybucji, aby karty z zachowaną w pamięci podręcznej stroną działały również podczas aktualizacji.
