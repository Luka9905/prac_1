Описание проекта

Данный проект представляет собой программу на языке C, которая предназначена для копирования содержимого файлов. Программа может работать как с файлами, так и со стандартным вводом, обеспечивая гибкость в использовании.

Функционал программы

Программа выполняет следующие функции:

1. Копирование из стандартного ввода: Если при запуске программы не указаны аргументы командной строки, она будет считывать данные из стандартного ввода (stdin) и выводить их в стандартный вывод (stdout).

2. Копирование из файлов: Если указаны имена файлов в качестве аргументов командной строки, программа будет открывать каждый файл по очереди, считывать его содержимое и выводить его в стандартный вывод.

Входные данные

Программа принимает данные следующими способами:

1)Стандартный ввод: Если аргументы не указаны, программа ожидает ввода данных от пользователя через терминал.

2)Файлы: При указании одного или нескольких имен файлов в качестве аргументов командной строки программа будет пытаться открыть и прочитать каждый из них.

Выходные данные

Программа выводит данные следующим образом:

Стандартный вывод: Все считанные данные (либо из стандартного ввода, либо из файлов) выводятся в стандартный вывод, который обычно отображается в терминале или может быть перенаправлен в другой файл.

Обработка ошибок

1)Если программа не может открыть указанный файл, она выведет сообщение об ошибке и завершится с кодом 1.

2)Если произойдет ошибка при записи в стандартный вывод, программа выведет соответствующее сообщение и завершится с кодом 2.

Аналоги в Linux
В Linux существует множество утилит с похожим функционалом. Одной из самых известных является команда cat, которая также позволяет выводить содержимое файлов на экран или объединять несколько файлов. Пример использования команды cat:
cat file1.txt file2.txt
Эта команда выведет содержимое file1.txt, а затем file2.txt в стандартный вывод.
