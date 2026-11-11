# Instrukcje Codex — repozytorium dwd

- Repozytorium było puste w chwili tworzenia tych instrukcji. Nie przypisuj mu celu, technologii, produkcyjnej bazy ani zależności bez osobnego zlecenia.
- Repozytorium jest **publiczne**: nie dodawaj tajnych danych, danych gości, tokenów, zrzutów baz ani jakichkolwiek plików prywatnych.
- Pierwszy kod lub konfigurację twórz dopiero na podstawie konkretnego zadania. Przed publikacją sprawdź licencje kopiowanych materiałów.

## Codex — zasady zapisu, kopiowania kodu i przeglądu zmian

- To są instrukcje pracy w repozytorium, **nie przyznanie uprawnień GitHub**. Dostęp Codexa autoryzuje właściciel konta w konfiguracji GitHub/Codex.
- Po zapoznaniu się z aktualnymi plikami i historią projektu Codex może tworzyć i modyfikować kod źródłowy, testy oraz dokumentację **w obrębie tego repozytorium**, pod warunkiem że repozytorium znajduje się w wybranym środowisku.
- Duże zmiany zapisuj na osobnej gałęzi `codex/<krótki-temat>`. Otwieraj pull request do `main`; nie nadpisuj i nie wykonuj force-push do głównej gałęzi. Istniejące niezależne zmiany zachowaj.
- Kod i niewrażliwe dokumenty można przenosić do innych repozytoriów użytkownika **wyłącznie w zakresie wyraźnego zadania**; zachowuj nazwy, licencje, historię i podział projektów.
- **Nie kopiuj między repozytoriami danych produkcyjnych, danych gości, danych osobowych, tokenów, haseł, kluczy API, plików `.env` ani kopii baz.** Nie zapisuj poświadczeń w Git ani w logach CI.
- Dla każdej zmiany uruchom dostępne testy i/lub kompilację. W PR opisz zmiany, wyniki testów, ograniczenia i ewentualne wymagane migracje.
- Nie zmieniaj wdrożonej produkcji, uprawnień użytkowników, baz Supabase, kluczy Vercel ani konfiguracji bezpieczeństwa bez osobnego zlecenia i weryfikacji.
