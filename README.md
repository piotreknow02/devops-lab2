# DevOps Lab 2

Ćwiczenie z podstaw Git i GitHub

### Cel
 ćwiczenie podstaw Git i GitHub

### Wykorzystane narzędzia
 - Git,
 - GitHub,
 - terminal

### Instrukcja uruchomienia/pracy
1. Utwórz repozytorium `devops-lab2` na GitHubie i sklonuj je lokalnie:
   `git clone https://github.com/TWOJ_LOGIN/devops-lab2.git`
2. Sprawdź stan repozytorium: `git status`, `git branch`.
3. Utwórz gałąź roboczą i przełącz się na nią:
   `git switch -c feature/update-readme`
4. Edytuj plik `README.md` (uzupełnij sekcje projektu).
5. Zapisz zmiany w commicie:
   `git add README.md` → `git commit -m "Update README for DevOps Lab 2"`
6. Wyślij gałąź na GitHuba: `git push -u origin feature/update-readme`
7. Na GitHubie utwórz Pull Request (źródło: `feature/update-readme`, cel: `main`).
8. Wykonaj code review, a następnie scal PR (Merge pull request).
9. Zaktualizuj lokalną gałąź główną:
   `git switch main` → `git pull origin main`

### Narzędzia zespołu
Git — historia zmian 
GitHub — Pull Requesty i code review 

### Autor
Piotr Nowakowski
