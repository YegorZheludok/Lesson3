# Иструкция команд языка *__Markdown__*

## *git __status__* 

* Показывает статут выбранной ветки 

## *git __branch__*

* Выводит список веток в репозитории. 
* Для создания новой ветки нужно после слова "branch" добавить "Имя ветки которую хочу создать".  
* Для удаления ветки нужно прописать после слова "branch" символ (-d) и Имя ветки что нужно удалить.

## *git __checkout__ (Имя ветки на которую нужно перейти)* 

* Команда для перехода между уже сущесвтующими ветками. 
* Так же эта команда позволяет переходить между разными commit. Для это нужно прописать gti checkout и первые 4 символа коммита на который хотим попасть. 

##  *git __log__ или git __log --graph__* 

* Выводит список комитов или во втором случае выводит список комитов ввиде  дерева\графа 
 
## *git __merge__ (Имя ветки которую нужно слить)*

* Сливает ветки между собой.
* Команда должна выполняться из той ветки в которую я хочу залить изменения.
* Могут быть конфликты 

## *git __init__*

* В той папке в которой мы запускаем данную программу она создает репозиторий. Проще говоря команда для старта работы в новой папке. 

## *git __add__ (Имя файла)*

* Данная команда добавляет файл в отслеживаемые. 

## *git __commit -m__ "В ковычках записываются изменения которые я сделал"* 

* Данная команда фиксирует наше текущее состояние 

## *git __diff__*

* Команда для просотра разницы между текущим и прошлым состоянием файлов. 

## *__clear__*

* Очищает строки терминала

## *git __clone__*

* Эта команда позволяет скопировать внешний репозиторий на ваш ПК. 

## *git __pull__* 

* Эта команда позволяет скачать все из текущего репозитория и автоматически сделает "*__merge__*" с нашей версией.

## *git __push__*

* Эта команда позволяет отправить нашу версию репорзитория на внешний репозиторий. *__ТРЕБУЕТ АВТОРИЗАЦИИ__* на внешнем репозитории.

## *Как сделать __pull request__* 

1. Делаем **fork**.
2. Делаем **clone СВОЕЙ** версии репозитория. 
3. Создаем новую ветку и в НЕЕ вносим свои изменения.
4. Фиксируем изменения (делаем commit).
5. Отправляем свою версию в **свой GitHub**.
6. На стайе GitHub нажимаем кнопку **__pull request__**.