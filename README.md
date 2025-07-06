# Zagadnienia na obronę

## Opis
Repozytorium zawiera notatki i opracowania zagadnień z różnych działów matematyki i statystyki przydatnych podczas przygotowań do obrony. Wszystkie materiały są zapisane w formacie LaTeX. Główny plik `zagadnienia.tex` łączy poszczególne działy (`algebra.tex`, `analiza.tex`, `numeryczne.tex`, `prawdopodobienstwo.tex`, `statystyka.tex`) w jeden dokument PDF.

## Kompilacja
Aby wygenerować plik PDF z opracowaniami, należy użyć kompilatora `pdflatex`. W terminalu wykonaj:

```bash
pdflatex zagadnienia.tex
```

W razie potrzeby komendę można powtórzyć kilkukrotnie, aby poprawnie wygenerować spis treści.

## Struktura repozytorium
- `zagadnienia.tex` – główny plik łączący wszystkie działy
- `algebra.tex`, `analiza.tex`, `numeryczne.tex`, `prawdopodobienstwo.tex`, `statystyka.tex` – osobne pliki dla każdego działu
- `zagadnienia.pdf` – wygenerowany dokument PDF

## Wymagania
Do kompilacji dokumentu wymagany jest system LaTeX. Rekomendowana jest dystrybucja TeX Live, ale można też użyć MikTeX (Windows) lub MacTeX (macOS).
