# Начальная работа с системой контроля версий

## Иструкция по работе с GitHub!
GitHub conflict

* *git config --global user.name "никнейм"* - представление в первый раз

* *git config --global user.email "почта"* - представление в первый раз

* *git --vesrion* - __Команда для проверка версии Git__

* *git init* - __Инициализируем пустой репозиторий__

* *git status* - __Проверяем текущее состояние файлов__

* *git add "название файла"* - **Добавляем версионность файлу**

* *git add .* - **Добавить версионность всем файлам к папке целиком** 

* *git commit -m "Massage"* - **Команда для фиксации изменений файлов**

* *git log* - **Вывод истории коммитов в хронологическом порядке** 

* *git log --graph* - **Вывод истории коммитов в виде дерева** 

* *git diff* - **Вывод изменений в текущий момент по отношению к последнему коммиту**

* *git branch* - **Вывод списка текущих веток**

* *git branch "название ветки"* - **Создать ветку**

* *git checkout -b "название ветки"* - **Создание ветки и одновременный переход в нее**

* *git checkout "хэш-номер комита")* - **Переход между коммитами (сохранениями)**

* *git checkout "название ветки")* - **Переход между ветками**

* *git merge "название ветки"* - **Перенос ветки в текущую**

ДЗ: 

## Инструкция по Markdown

Источники:

Инструкция по Markdown 1: https://www.markdownguide.org/basic-syntax/

Инструкция по Markdown 2: https://docs.microsoft.com/ru-ru/contribute/markdown-reference

### Выделение текста:

* Что бы выделить текст курсивом необходимо обрамить его звездочками (*) или знаком нижнего подчеркивания. Например *вот так* или _вот так_.

* Чтобы выделить текст полужирным, необходимо обрамить его звездочками или двойным знаком нижнего подчеркивания.  Например **вот так** или __вот так__.

* Альтернативные способы выделения текста жирным или курсивом нужны для того чтобы мы могли совмещать оба эти способа. Например _текст может быть выделен курсовом и при этом быть **полужирным**_.

### Списки:

Чтобы добавить ненумерованные списки необходимо пункты выделить звездочкой (*) или знаком (+). Например вот так:
* Элемент 1
* Элемент 2
+ Элемент 3
+ Элемент 4

Чтобы добавить нумерованные списки, необходимо пункты просто пронумеровать.
Например вот так:
1. Первый пункт
1. Второй пункт

### Работа с изображениями:

Чтобы вставить изображение в текс, достаточно написать следующее:

![Здесь должен был быть Олень!](deer.png)

* В квадратных скобках [ ] пишется текст если картинка не загузится, а в круглых ( ) завание файла с расширением которая лежит в той же папке.

* Чтобы git перестал отслеживать какой-либо файл или картинку достаточно в папке создать файл ".gitignore" и прописать там название файлов, которые Вы бы хотели чтобы Git игнорировал

### Ссылки:

Для того что бы сделать ссылку достаточно обрамить текст в квадратные скобки [ ] и далее без пробела вставить ссылку в круглых скобках ( ). Например вот так:

Моя люмимая поисковая система - [Duck Duck Go](https://duckduckgo.com/).

### Цитацы:

* Чтобы сделать цитаты необходимо добавить значок > перед абзацем. 

* Чтобы цитата состояла из нескольких абзацев необходимо добавить значок > на пустой строке между абзацами

* Чтобы сделать вложенную цитату необходимо поставить 2 значка >> перед влюженной цитатой

Например вот так:

> Уважать всякого человека, как самого себя, и поступать с ним, как мы желаем, чтобы с нами поступали, — выше этого нет ничего.
> 
> Конфуций.
>
>> Жизнь - это то, что с тобой происходит, пока ты строишь планы

ДЗ после 2 семинара:

Ветка master:

Ветка 1: добавляем информацию в векте 1

Ветка 2: в мастере выглядит так
Ветка 2: а в ветке 2 выглядит вот так

Ветка 3: тут пишем текст который хотим добавить в мастер

Ветка 4: в 4 ветке создаем конФликт (специально делаю ошибку в слове)
