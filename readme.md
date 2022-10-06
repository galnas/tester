# Словарь


Регистрация

> git config --global user.name "введите имя пользователя" <br>
git config --global user.email "введите свою почту"

Клонирование репозитория
> git clone "ссылка на репозиторий"

Создание локально нового репозитория
>git init 

Добавляет изменения рабочего каталога в проиндексированный файл 
>git add .

Операция отмены 
>git restore 

Создание нового подключения к удаленновму репозиторию
>git remote add <name> <url>

Узнать какие файлы в каком состоянии находятся 
>git status <br>
упрощенный вывод - git status -s

Добавить файл в индекс 
>git commit -m "добавить коментарий"

Просмотр информации о файлах в индексе и рабочем дереве
> ls -la

Отоображение объекта в простом виде 
>git show

Перечисление коммитов, сделанные в репозитории 
>git log

Создание ветки
>git checkout -b "название ветки"

Переход из ветки в основной
>git checkout main 

Узнать в каком репозитории сейчас 
>git remote -v

Перенос данных из ветки в основную 
>git merge "название ветки"

Преостановить работу 
>git stash pop

Вычисления разницу между любыми двумя Git деревьями
>git diff 

Операция отмены 
>git restore

Выгрузить локального репозитория в удаленный
>git push


