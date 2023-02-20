
### Homework XML

| Задание |            Решение |
|------------- |------------- 
|Создать внешний репозиторий c названием XML| **Create a new repository** (*Repository name* - XML, Public, Add a README file -> *Create repository*)|
|Клонировать репозиторий XML на локальный компьютер| `git clone` [https://github.com/ratenok/XML.git](https://github.com/ratenok/XML.git) |
|Внутри локального XML создать файл “new.xml”| `touch` new.xml
|Добавить файл под гит |`git add` new.xml
|Закоммитить файл | `git commit -m` "add new.xml file"|
|Отправить файл на внешний GitHub репозиторий | `git push` |
|Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML |`cat >>new.xml` -> *внести необходимую информацию* -> `enter` -> `ctr+C`|
|Отправить изменения на внешний репозиторий | `git status` `git add` new.json `git commit -m` "update new.xml file" `git push` |
|Создать файл preferences.xml | `touch` preferences.xml |
|В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML |`cat >> preferences.xml` -> *внести необходимую информацию* -> `enter` -> `ctr+C`|
|Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML | `cat > skills.xml` -> *внести необходимую информацию* -> `enter` -> `ctr+C`|
|Сделать коммит в одну строку | `git add .` `git commit -m` "add files"
|Отправить сразу 2 файла на внешний репозиторий | `git push` |
|На веб интерфейсе создать файл bug_report.xml | `Add file` -> `create new file` -> *ввести название* **bug_report.xml** |
|Сделать Commit changes (сохранить) изменения на веб интерфейсе | **Commit new file** |
|На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML | *нажать на кнопку* **Edit file** -> *отредактировать* |
|Сделать Commit changes (сохранить) изменения на веб интерфейсе | *отредактировав файл*, нажать на кнопку **Commit changes** |
|Синхронизировать внешний и локальный репозиторий XML | `git pull`|