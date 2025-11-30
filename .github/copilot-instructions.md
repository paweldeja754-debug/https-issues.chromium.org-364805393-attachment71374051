# Instrukcje dla AI coding agent (krótkie)

Ten plik zawiera skondensowane, praktyczne wskazówki dla AI coding agents pracujących nad tym repozytorium.

**Repo Overview**
- **Pliki kluczowe:** `README.md` — jedyny plik w repozytorium, jego nazwa sugeruje, że to załącznik do zgłoszenia Chromium (attachment). Repozytorium nie zawiera kodu ani skryptów.
- **Cel repo:** Przechowywanie pojedynczego pliku/załącznika (brak aplikacji do uruchomienia).

**Co zrobić najpierw**
- **Sprawdź zawartość:** Otwórz `README.md` i inne pliki w repo (jeśli wystąpią) przed wprowadzeniem jakichkolwiek zmian.
- **Jeśli brakuje kontekstu:** Poproś o wyjaśnienia — np. czy mamy dodać kod, naprawić błąd, dopisać dokumentację, czy po prostu przenieść zasób.

**Kiedy edytować/commitować**
- **Małe, jasne zmiany:** Stwórz branch z krótką nazwą (`update/readme` lub `add/copilot-instructions`) i otwórz PR do `main` z opisem "Dlaczego" i "Co" zrobiono.
- **Brak testów/CI:** Nie zakładaj istnienia testów ani procesu budowania — zapytaj autora jeśli potrzebne są polecenia budowania lub testowania.

**Wzorce i konwencje specyficzne dla repo**
- To repo nie zawiera konwencji kodowania ani struktury katalogów. Nie wprowadzaj skomplikowanych szablonów bez uprzedniej zgody opiekuna projektu.

**Integracje i zależności**
- Brak wykrywalnych zewnętrznych integracji (nie znaleziono `package.json`, `pyproject.toml`, `Dockerfile`, itp.). Przed dodaniem zależności zapytaj o preferowaną technologię.

**Przykładowe polecenia i checklista przed PR**
- Otwórz `README.md` i upewnij się, że proponowane zmiany są zgodne z intencją repo.
- Utwórz branch, wykonaj mały commit z jednym celem i otwórz PR z jasnym opisem.

**Przydatne wskazówki dla agenta**
- Jeśli zadanie nie jest jednoznaczne, zakładaj brak kontekstu i zaproś opiekuna projektu do doprecyzowania wymagań.
- Nie dodawaj kodu ani konfiguracji buildów, jeśli nie istnieje żaden sygnał w repo że są potrzebne.
- Dokumentuj założenia w opisie PR (co założyłeś i dlaczego).

Jeśli chcesz, mogę rozszerzyć ten plik o sekcję „When this repo grows” z szablonami commitów, PR i struktury katalogów — chcesz, żeby to zrobić?
