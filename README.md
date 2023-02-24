# JSON
4) Создать внешний репозиторий c названием JSON === На вэбе Repositories --> New --> Repos Name:JSON --> Check "Add a README file" --> Press "Create repository"
5) Клонировать репозиторий JSON на локальный компьютер === `git clone <repository SSH>`
6) Внутри локального JSON создать файл "new.json" === `touch new.json`
7) Добавить файл под гит === `git add new.json`
8) Закоммитить файл === `git commit -m "comment"`
9) Отправить файл на внешний GitHub репозиторий === `git push`
10) Отредактировать содержание файла “new.json” написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата) === `vim new.json` ---> input data ---> esc ---> enter ":wq".
11) Отправить изменения на внешний репозиторий === `git commit -am "comment" && git push`
12) Создать файл preferences.json === `touch preferences.json`
13) В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, страна которую хотели бы посетить)  === `vim preferences.json` ---> insert data ---> esc ---> enter ":wq"
14) Создать файл skills.json  === `touch skills.json`
15) Отправить сразу 2 файла на внешний репозиторий === `git add . && git commit -m "comment" && git push`
16) На веб интерфейсе создать файл bug_report.json === Add file --> Create new file --> Name: bug_report.json
17) Сделать Commit changes (сохранить) изменения на веб интерфейсе === Commit New File
18) На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON === Choose bug_report.json --> Edit this file
19) Сделать Commit changes (сохранить) изменения на веб интерфейсе === Commit changes
20) Синхронизировать внешний и локальный репозиторий JSON === `git pull`
