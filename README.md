### 1. Создание репозитория под названием "AboutGit":

    1)
    
      `  
        $ cd ~/dev/AboutGit 
        $ git init                 
      `  
        (инициализация)
    

    2) Чтобы "разгитить" папку, переходим в неё и набираем 
        (это в случае если не хотим, чтобы она была репозиторием):

        $ rm -rf .git       (удаление)
        (-r значит рекурсивно(recursive), -f значит принудительно(force) или заставить)

    3) проверка состояния репозитория:
        $ git status        (набирается в папке репозитория)
 --- 
### 2. Подготовка файлов к сохранению:

    $ git add --all
        или
    $ git add .
---
### 3. Делаем коммит:

    $git commit -m 'Первый коммит'
---
### 4. Просмотр истории коммитов:

    $git log
---