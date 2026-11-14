# Matematyka – materiały dla uczniów

- `index.html` – **strona główna**: kafelki Matematyka techniczna, Matematyka 4T, Matematyka 1A.
- `matematyka-techniczna.html` – **matematyka techniczna, dział Wektory**: lista tematów lekcji i materiały przed pracą klasową.
- `matematyka-4t.html` – **klasa 4T, dział 2. Geometria analityczna**: tematy 1–9 i materiały przed pracą klasową.
- `4t-*.html` – strony tematów działu (teoria, rysunki, interaktywne narzędzia, zadania z rozwiązaniami, trening ze sprawdzaniem) i `4t-geometria-powtorka.html` (wymagania, ściąga, próbny sprawdzian, generator). Pliki są składane skryptem `_materialy-nauczycielskie/narzedzia/mt-4t/build.py` – poprawki najlepiej wprowadzać tam i budować od nowa.
- `matematyka-1a.html` – strona klasy 1A (dział 2. Język matematyki).
- `prostopadlosc-rownoleglosc.html` – **Warunek prostopadłości i równoległości wektorów** (teoria, przykłady, interaktywny kalkulator, zadania z rozwiązaniami).
- `powtorka.html` – **Opracowanie całego działu przed pracą klasową** (wymagania z checklistą, teoria z rysunkami, zadania z parametrem, dowody, ściąga, próbny sprawdzian, generator zadań).

## Publikacja na GitHub Pages

1. Wypchnij repozytorium na GitHub.
2. **Settings → Pages → Build and deployment**: Source = *Deploy from a branch*, Branch = `main`, folder `/ (root)`.
3. Po chwili strona będzie dostępna pod adresem `https://<login>.github.io/mt/`.

Wzory renderuje KaTeX (CDN cdnjs), więc nie trzeba niczego budować.
