# MojePierwszeRepo

To repozytorium służy do nauki pracy z Git i GitHub: tworzenia branchy, pull requestów i pracy z issue. Zawiera proste przykłady i ćwiczenia — nie jest to projekt produkcyjny.

## Co robi projekt
- Służy jako repozytorium ćwiczeniowe do nauki podstaw kontroli wersji.
- Pozwala ćwiczyć tworzenie branchy, pull requestów oraz rozwiązywanie issue.
- Możesz dodawać proste przykłady kodu i instrukcje uruchomienia w miarę rozwoju repozytorium.

## Jak uruchomić / jak korzystać
1. Sklonuj repozytorium:
   ```
   git clone https://github.com/okrzanowska/MojePierwszeRepo.git
   cd MojePierwszeRepo
   ```

3. Utwórz nowy branch na potrzeby zmian:
   ```
   git checkout -b moja-zmiana
   ```
   
5. Dodaj lub zmodyfikuj pliki, a następnie zatwierdź zmiany:
   ```
   git add .
   git commit -m "Dodano/zmodyfikowano pliki: krótki opis zmian"
   ```
   
7. Wypchnij branch na GitHub i otwórz pull request:
   ```
   git push origin moja-zmiana
   ```
   (Na GitHub: New pull request -> wybierz `moja-zmiana` -> `main`)

9. Zgłaszanie issue:
   Na stronie repozytorium wybierz zakładkę "Issues" i kliknij "New issue".
