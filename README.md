# AI Crypto Market Lab — publiczna strona informacyjna

**To repozytorium jest PUBLICZNE** i zawiera **wyłącznie statyczną stronę informacyjną**, politykę prywatności oraz arkusz stylów. Właściwy kod projektu badawczego, dane Kraken i ustawienia OAuth znajdują się poza tym repozytorium.

## Publikacja w GitHub Pages — jeden krok w interfejsie

1. Otwórz **Settings → Pages** dla tego repozytorium.
2. W sekcji **Build and deployment** wybierz **Deploy from a branch**.
3. Wskaż gałąź **main**, katalog **/(root)** i naciśnij **Save**.
4. Po zakończeniu publikacji sprawdź stronę:
   - https://callnoste-source.github.io/AI-Crypto-Market-Lab-Site/
   - https://callnoste-source.github.io/AI-Crypto-Market-Lab-Site/privacy.html

Linków **nie dodawaj do Google OAuth** przed sprawdzeniem, czy rzeczywiście działają.

## Ważne ograniczenie Google OAuth

GitHub Pages nie gwarantuje weryfikowalnej własności domeny github.io w Google Search Console. Google wymaga weryfikacji domeny produkcyjnej aplikacji i może odrzucić aplikację pod adresem współdzielonej domeny, której deweloper nie kontroluje.

To repozytorium NIE jest dowodem weryfikacji marki OAuth. W razie konieczności można wykorzystać własną domenę, lecz **nie kupuj jej bez potwierdzenia faktycznej potrzeby**. Polityka prywatności wymaga przeglądu przed uruchomieniem właściwej integracji Google Drive: wszystkie deklaracje muszą odzwierciedlać rzeczywistą implementację i obsługę danych.

## Zasady bezpieczeństwa

- Nie dodawaj tokenów, plików JSON OAuth, kodu strategii, danych rynkowych, logów z danymi poufnymi ani danych osobowych.
- Strona nie inicjuje OAuth i nie zbiera kluczy dostępu.
- Przed publikacją zmian w polityce prywatności przejrzyj faktyczny przepływ danych.
- Na stronie nie ma zewnętrznego JavaScriptu, formularzy ani analityki właściciela projektu.

## Pliki

- index.html — publiczna strona główna.
- privacy.html — opis prywatności strony i planowanej integracji Google Drive.
- styles.css — lokalne style, bez zewnętrznych bibliotek.
