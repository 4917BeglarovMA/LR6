Регистрируюсь на GitHub, после чего скачиваю Git

Ввожу user.name и user.email

![](screen/1.png)

Копирую сохранённые данные с профиля

![](screen/2.png)

Перехожу в созданную папку Lr6

![](screen/3.png)

Запрашиваю изменения с GitHub

![](screen/4.png)

Запрашиваю историю ветки

![](screen/5.png)

Вывожу историю ветки

![](screen/6.png)

Получаю список веток

![](screen/7.png)

История ветки Branch1

![](screen/8.png)

Информация о изменениях

![](screen/9.png)
![](screen/10.png)
![](screen/11.png)

Перехожу в ветку master и сливаю ее с Branch1

![](screen/12.png)

Вывожу статус и смотрю конфликты

![](screen/13.png)

Добавляю файл txt после его изменения

![](screen/14.png)

Проверяю статус, конфликтов нет

![](screen/15.png)

Коммитю изменения

![](screen/16.png)

Удаляю ветку branch1

![](screen/17.png)

Добавляю файл 1.txt

![](screen/18.png)

Коммитю

![](screen/19.png)

Добавляю файл 2.txt

![](screen/20.png)

Коммитю

![](screen/21.png)

Сбрасываю настройки

![](screen/22.png)

Создаю ветку Doklad

![](screen/23.png)

Список моих коммитов

![](screen/24.png)
![](screen/25.png)

Заливаю все на свой GitHub

![](screen/26.png)

Скриншот создания файла в GitHub

![](screen/27.png)


Лог команд

git config --global user.name "4917BeglarovMA "

git config --global user.email fox00900@mail.ru

git clone https://github.com/4917BeglarovMA/LR6

cd LR6

git pull

git log

git branch

git checkout branch1

git log

git log -p

git checkout master

git merge branch1

git status

git add mergefile.txt

git status

git commit -m "Commit changes"

git branch -d branch1

git add 1.txt

git commit -m "text1.txt"

git add 2.txt

git commit -m "text2.txt"

git reset --hard HEAD~1

git checkout -b Doklad

git log

git push --all https://github.com/4917BeglarovMA/LR6

git add Image

git commit -m "Added file Image"

git push --all https://github.com/4917BeglarovMA/LR6
