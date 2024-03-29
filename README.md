# Лабораторная работа по Python

Этот проект создан для выполнения лабораторной работы по языку программирования Python. Программа эмулирует работу с числовой последовательностью, читая, обрабатывая и выводя лексемы по определенному правилу. 
## Техническое задание

**ЗАДАНИЕ:** Написать программу, которая читая символы из бесконечной последовательности (эмулируется конечным файлом, читающимся поблочно), распознает, преобразует и выводит на экран лексемы по определенному правилу. Лексемы разделены пробелами. Преобразование делать по возможности через словарь. Для упрощения под выводом числа прописью подразумевается последовательный вывод всех цифр числа. Регулярные выражения использовать нельзя. <br>
**ВАРИАНТ 12.** Натуральные числа, содержащие более 3 цифр. Вывести количество таких чисел. Максимальное число вывести прописью.
## Ограничение последовательности чисел

В задании указано работать с бесконечной последовательностью чисел. Однако, в целях практичности и предотвращения проблем с использованием дискового пространства, я решил ограничить последовательность 1000 числами. Это позволяет программе эффективно работать в ограниченных условиях и избежать проблем с переполнением диска.

## Содержание проекта

- `lab1.py`: Основной код программы, решающей поставленную задачу.
- `lab1_1.py`: Второй вариант программы, решающей поставленную задачу. В отличие от первоначальной версии, эта программа не перезаписывает файл `input.txt` при каждом запуске. Вместо этого, она добавляет новые числа к уже существующим данным, сохраняя их в файле. Это позволяет постепенно наращивать объем числовой последовательности. Так же реализована проверка введенных символов (если файл `input.txt` изменен *вручную*).
- `input.txt`: Файл, в котором сохраняется числовая последовательность.

## Запуск программы

1. Запустите `lab1.py` в вашей среде разработки, чтобы создать файл `input.txt` с числовой последовательностью. и вывести результат в консоли.
2. Для тестирования проекта запустите `lab1_1.py` в вашей среде разработки, чтобы создать/наполнить файл `input.txt` с числовой последовательностью и вывести результат в консоли. При ручном корректировании файла `input.txt` программа проверяет введенные данные, при обнаружении ненатурального числа/иного символа - программа выдаст ошибку.

## Зависимости

Программа написана на Python. Нет необходимости в установке дополнительных библиотек.

## Информация о разработчике

[Казаров Дмитрий]
[Студент ИСТбд-11]
[Преподаватель: Шишкин Вадим Викторинович]


