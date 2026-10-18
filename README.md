# Wstęp do programowania — ćwiczenia

**Języki programowania (Python)** · Psychologia i informatyka, I rok · Uniwersytet SWPS · 2026/2027

Notatniki Jupyter z ćwiczeniami do warsztatów. Każde zajęcia mają osobny folder.

## Zajęcia

| Zajęcia | Temat | Notatnik | Colab |
| --- | --- | --- | --- |
| 1 | `print`, zmienne i typy danych | [zajecia-01-cwiczenia.ipynb](zajecia-01/zajecia-01-cwiczenia.ipynb) | [![Otwórz w Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/marcinkieruzel/wstep-do-programowania-swps/blob/main/zajecia-01/zajecia-01-cwiczenia.ipynb) |
| 2 | Zmienne jako pudła, teksty, konwersja, warunki i pętle; `match`, kalkulator, struktury danych | [zajecia-02-cwiczenia.ipynb](zajecia-02/zajecia-02-cwiczenia.ipynb) | [![Otwórz w Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/marcinkieruzel/wstep-do-programowania-swps/blob/main/zajecia-02/zajecia-02-cwiczenia.ipynb) |

## Jak pracować z ćwiczeniami

### Google Colab — bez instalacji

1. Kliknij przycisk **Open in Colab** przy zajęciach.
2. Zaloguj się na konto Google.
3. Kliknij u góry **Skopiuj na Dysk** (*Copy to Drive*) i pracuj na swojej kopii. Bez tego Twoje odpowiedzi znikną po zamknięciu karty.

### VS Code — na własnym komputerze

1. Pobierz repozytorium: zielony przycisk **Code**, potem **Download ZIP** — albo w terminalu:
   ```bash
   git clone https://github.com/marcinkieruzel/wstep-do-programowania-swps.git
   ```
2. Otwórz folder w VS Code i utwórz środowisko: Ctrl+Shift+P (na macOS Cmd+Shift+P), wybierz **Python: Create Environment**, potem **Venv** — tak jak na zajęciach 1.
3. Otwórz plik `.ipynb`. Jeśli VS Code zaproponuje rozszerzenie **Jupyter** (Microsoft), zainstaluj je.
4. W prawym górnym rogu kliknij **Select Kernel** i wybierz `.venv`. Jeśli VS Code poprosi o pakiet **ipykernel**, kliknij *Install*.

### Zasady

- Uruchamiaj komórki **po kolei, od góry**: Shift+Enter albo przycisk uruchamiania obok komórki.
- **Od zajęć 2** pod każdym zadaniem jest blok **Oczekiwany wynik**: napisz kod pod `# Twój kod`, uruchom komórkę i porównaj to, co wypisał program. Komórki sprawdzające i oznaczenia trudności są tylko w zajęciach 1.
- Kilka komórek **celowo kończy się błędem** — tak uczysz się czytać komunikaty Pythona. Dlatego *Run All* zatrzyma się w połowie: uruchamiaj komórki pojedynczo.
- Komórki opisane jako do uruchomienia ręcznie czekają, aż wpiszesz dane z klawiatury (`input()`). Pętlę, która się nie kończy, zatrzymasz przyciskiem Stop (*Interrupt*).
- Wszystkie dane w zadaniach (wyniki, czasy reakcji, wiek osób badanych) są fikcyjne.
