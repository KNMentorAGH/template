# [Project Name]

Ten projekt został wygenerowany z szablonu

## 🛠️ Standardy pracy
Projekt korzysta z globalnych standardów. Zanim zaczniesz, zapoznaj się z:
- [Zasady współpracy (Contributing)](https://github.com/KNMentorAGH/.github/blob/main/.github/CONTRIBUTING.md)
- [Baza wiedzy (SOLID, VSA, Naming)](https://github.com/KNMentorAGH/.github/tree/main/compendium)

## 🚀 Szybki start
1. **Instalacja narzędzi**: jeśli pracujesz w Pythonie, zainstaluj rozszerzenie Ruff w swoim edytorze (VS Code/PyCharm) oraz lokalnie przez pip install ruff. Dzięki temu błędy zobaczysz przed wysłaniem kodu.
2. **Czyszczenie**: Szablon jest uniwersalny - aby nie obciążać procesów CI/CD:
   - Jeśli projekt jest w Pythonie — usuń plik `.editorconfig`
   - Jeśli projekt jest w C# — usuń plik `pyproject.toml`
3. **Konfiguracja**: Upewnij się, że masz włączoną opcję `Format on Save` w IDE

## 🤖 Automatyzacja
- **English Only**: Cały kod, nazwy zmiennych, komentarze dokumentacji oraz wiadomości commitów muszą być w języku angielskim.
- **No Inline Comments**: Nie piszemy komentarzy wewnątrz metod. Kod ma być czytelny sam w sobie. Jeśli musisz coś wyjaśnić, użyj dokumentacji.
- **Auto-Format**: Każdy Pull Request automatycznie uruchamia bota, który poprawi Twoje spacje, wcięcia i porządek w importach. Jeśli bot wprowadzi zmiany, pobierz je do siebie (git pull) przed dalszą pracą.
- **Naming**: Nazwy gałęzi (branches) muszą być zgodne z konwencją (np. feat/feature-name lub fix/bug-name).
