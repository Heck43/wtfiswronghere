# 13 challenge

## описание ошибки
в этом испытании было три ошибки:
1. пропущена закрывающая одиночная кавычка в строке `three_mul = 'fizz` (`SyntaxError: EOL while scanning string literal`).
2. пропущено двоеточие в конце объявления цикла `for i in range(1,max_num)` (`SyntaxError: invalid syntax`).
3. опечатка в имени вызываемой функции `fizzbuzzy(100)` вместо `fizzbuzz(100)` (`NameError: name 'fizzbuzzy' is not defined`).

## решение
1. закрыли кавычку в `three_mul = 'fizz'`.
2. добавили двоеточие в конец строки цикла `for i in range(1,max_num):`.
3. исправили вызов функции на `fizzbuzz(100)`.
теперь файл запускается и работает без ошибок.

## что делает функция
функция `fizzbuzz(max_num)` выполняет классический вывод fizzbuzz для чисел от 1 до `max_num - 1` с исправленным синтаксисом и кавычками.
