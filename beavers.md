1. Forking workflow
    ```bash
    FORK
    git clone git@github.com:<nazwa>/beavers-git.git
    git remote add upstream git@github.com:hanngos/beavers-git.git
    ```
2. PRka
    ```bash
    git checkout -b <nazwa nowego brancha>
    DODAJ SWOJE IMIE W PLIKU README.md
    git add README.md
    git commit -m "Komentarz"
    git push origin <nazwa nowego brancha>
    STWÓRZ PRkę na GH
    ```
3. Konflikty
    ```bash
    ROZWIĄŻ KONFLIKTY
    ```
4. Rebase
    ```bash
   git rebase upstream/main
   git add
   git rebase --continue
   git push origin <nazwa brancha> -f
    ``` 
5. May the force be with you (-f) + git log
   ```bash
   git log --pretty=oneline
   git reset <hash commita>
   ```