# Инструкция для работы с Git и удалёнными репозиториями

## Что такое Git?
Git - это одна из реализаций распределённых систем контроля версий, имеющая как и локальные, так и удалённые репозитории. Является самой популярной реализацией систем контроля версий в мире.

## Подготовка репозитория
Для создание репозитория необходимо выполнить команду *git init*  в папке с репозиторием и у Вас создаться репозиторий (появится скрытая папка .git)

## Создание коммитов

### Git add
Для добавления измений в коммит используется команда *git add*. Чтобы использовать команду *git add* напишите *git add <имя файла>*

### Просмотр состояния репозитория
Для того, чтобы посмотреть состояние репозитория используется команда *git status*. Для этого необходимо в папке с репозиторием написать *git status*, и Вы увидите были ли измения в файлах, или их не было.

### Создание коммитов
Для того, чтобы создать коммит(сохранение) необходимо выполнить команду *git commit*. Выполняется она так: *git commit -m "<сообщение к коммиту>*. Все файлы для коммита должны быть ***ДОБАВЛЕНЫ*** и сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО***.

## Перемещение между сохранениями
Для того, чтобы перемещаться между коммитами, используется команда *git checkout*. Используется она в папке с пепозиторием следующим образом: *git checkout <номер коммита>*

## Журнал изменений
Для того, чтобы посмтреть все сделанные изменения в репозитории, используется команда *git log*. Для этого достаточно выполнить команду *git log* в папке с репозиторием

### Создание ветки

Для того, чтобы создать ветку, используется команда *git branch*. Делается это следующим образом в папке с репозиторием: *git branch <название новой ветки>*

## Слияние веток

Для того чтобы дабавить ветку в текущую ветку используется команда *git merge <name branch>*

## Удаление веток
Для удаления ветки ввести команду "git branch -d 'name branch'"
## Дополнительные команды

1. Просмотреть список файлов в каталоге необходимо ввести команду *ls*

2. Удалить файл *rm <имя файла>*

3. Cоздать папку *mkdir <имя папки>*

4. Вставить сетевое изображение ![Картинка]<адрес в круглых скобках>

пример
![Картинка](https://all-t-shirts.ru/goods_images/ru117078II00082d7b00b7f86fef1a52605b92cd0b9a7.jpg)

5. Для обозначения цитат используется знак «больше» («>»)

Пример:
>Пример цитаты
>>Пример вложенной цитаты второго уровня
>>>Вложенная цитата третьего уровня

6. Для обозначения ссылок используется [**Адрес**]

[Пример] [https://img1.akspic.ru/crops/2/2/4/0/50422/50422-senokosnoye_ugodye-pole-selskoe_hozyajstvo-zakat-risovoe_pole-2560x1440.jpg]

7. Для записи в файл cat > file

8. Что бы выделить текст полужирным курсивным шрифтом необходимо указать три звезды до и после слова или предложения

***Пример***
 
to be continied
 
 Вносим корректировку
