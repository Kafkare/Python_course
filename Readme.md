# Задание: 
## **Информация о проекте**
Необходимо написать проект, содержащий функционал работы с заметками. Программа должна уметь создавать заметку, сохранять её, читать список заметок, редактировать заметку, удалять заметку.

## **Как сдавать проект**
Для сдачи проекта необходимо создать отдельный общедоступный репозиторий (Github, gitlub, или Bitbucket). Разработку вести в этом репозитории, использовать пул реквесты на изменения. Программа должна запускаться и работать, ошибок при выполнении программы быть не должно.

## **Критерии оценки**
Приложение должно запускаться без ошибок, должно уметь сохранять данные в файл, уметь читать данные из файла, делать выборку по дате, выводить на экран выбранную запись, выводить на экран весь список записок, добавлять записку, редактировать ее и удалять.


# Описание проекта:

1. Проект расположен на  [Github](https://github.com/Kafkare/Python_course/tree/main/)
2. В проекте были использованы Pull requests на изменение с рабочей ветки dev в итоговую ветку main
3. Приложение Журнал заметок выполняет следующий функционал:
- вывод журнала заметок
- вывод журнала заметок по id
- вывод журнала заметок по дате
- добавление заметок в журнал заметок
- изменение заметки по id в журнале заметок
- удаление заметки по id в журнале заметок
- весь журнал заметок хранится в текстовом файле
4. Структура проекта:
- note.py - класс заметка
- сontroller.py - выполнение основной логики приложения
- commands.py - методы основных команд по работе с заметками
- counter.py - счетчик для автоматического id заметки
- loadFromFile.py - извлечение данных журанала заметок из файла
- writeToFile.py - запись данных журнала заметок в файл
- menuTemplates.py и userMenuConsole.py  - пользовательский интерфейс
