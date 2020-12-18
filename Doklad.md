Регистрируюсь на GitHub, после чего скачиваю Git

Ввожу user.name и user.email

![](Screen/1.png)

Копирую сохранённые данные с профиля

![](Screen/2.png)

Перехожу в созданную папку Lr6

![](Screen/3.png)

Запрашиваю изменения с GitHub

![](Screen/4.png)

Запрашиваю историю ветки

![](Screen/5.png)

Вывожу историю ветки

![](Screen/6.png)

Получаю список веток

![](Screen/7.png)

История ветки Branch1

![](Screen/8.png)

Информация о изменениях

![](Screen/9.png)
![](Screen/10.png)
![](Screen/11.png)

Перехожу в ветку master и сливаю ее с Branch1

![](Screen/12.png)

Вывожу статус и смотрю конфликты

![](Screen/13.png)

Добавляю файл txt после его изменения

![](Screen/14.png)

Проверяю статус, конфликтов нет

![](Screen/15.png)

Коммитю изменения

![](Screen/16.png)

Удаляю ветку branch1

![](Screen/17.png)

Добавляю файл 1.txt

![](Screen/18.png)

Коммитю

![](Screen/19.png)

Добавляю файл 2.txt

![](Screen/20.png)

Коммитю

![](Screen/21.png)

Сбрасываю настройки

![](Screen/22.png)

Создаю ветку Doklad

![](Screen/23.png)

Список моих коммитов

![](Screen/24.png)
![](Screen/25.png)

Заливаю все на свой GitHub

![](Screen/26.png)

Скриншот создания файла в GitHub

![](Screen/27.png)


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
