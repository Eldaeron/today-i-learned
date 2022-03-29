# today-i-learned
Eleks [Тестовий репозиторій]

![image](https://user-images.githubusercontent.com/23397333/160283892-aef152ae-239e-419f-ab42-20ce849b9234.png)

## 1. Ініціалізація git в директорії
```
$ git init
Initialized empty Git repository in desktop/module-git/
```

## 2. Додавання нових файлів до git
```
$ git add first-file.txt
```
  
## 3. Поточний статус git
```
  $ git status
  - On branch master
  - Your branch is up-to-date with 'origin/master'.
  - Changes to be committed:
  - (use "git reset HEAD <file>..." to unstage)

  - new file:   first-file.txt
 ```
  
## 4. Збереження змін у комітах (commit)
```$ git commit -m "First-file test"
  - [master 999999] First-file test
  - 1 files changed, 1 insertions(+)
 ```

## 5. Основи гіта: https://learngitbranching.js.org/?locale=uk
```  - Команда для створення нових гілок: git branch <name>; git branch bugFix
  - Команда перейти на новостворену гілку, або на основну <main>: git checkout <name>; git checkout bugFix
  - Команда для злиття гілок в одну гілку: git merge <name>; git merge bugFix
  - Альтернативна команда для злиття (ребейс): git rebase <name>; git rebase main
```
  
