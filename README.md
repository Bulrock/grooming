# Grooming

Prosty landing page MVP dla salonu groomerskiego w języku polskim.

## Jak ustawić link do formularza

1. Wejdź w `Settings -> Secrets and variables -> Actions -> Variables`.
2. Dodaj zmienną repozytorium `BOOKING_FORM_URL`.
3. Wartość ustaw na pełny adres formularza, np. `https://twojadomena.pl/formularz`.
4. Włącz GitHub Pages dla workflow Actions, jeśli nie jest jeszcze aktywne.

Po deployu workflow podmieni placeholder w `index.html` i przyciski "Umów wizytę" będą prowadzić do wskazanego formularza.
