
# Opis

Repozytorium zawiera kod źródłowy do generowania dokumentacji w Sphinx, w formie pliku PDF. Dokumentacja składa się z kilku rozdziałów i strony tytułowej.

## Struktura Repozytorium

 **`source`**: Zawiera pliki źródłowe w formacie ReStructuredText (RST). Każdy plik RST odpowiada jednemu rozdziałowi.

## Generowanie PDF

Aby wygenerować plik PDF, użyj narzędzi takich jak Sphinx oraz Sphinx LaTeX Builder. Oto kroki:

1. Uruchom `sphinx-build -b latex . _build` w głównym katalogu.
2. Przejdź do katalogu `_build`.
3. Uruchom `make latexpdf`.

Plik PDF zostanie wygenerowany w katalogu `_build/latex`.

#Autor
Szymon Blatkowski
