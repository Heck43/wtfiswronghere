# 08 challenge

## описание ошибки
метод `fizzbuzz` определен внутри класса `Fizz_Buzz`, но не принимает в качестве первого аргумента ссылку на экземпляр класса (`self`). при вызове `fizzbuzz_obj.fizzbuzz(100)` python неявно передает объект класса первым аргументом, что вызывало `TypeError: fizzbuzz() takes 1 positional argument but 2 were given`.

## решение
добавили параметр `self` первым аргументом в определение метода: `def fizzbuzz(self, max_num):`.
теперь вызов метода класса отрабатывает корректно.

## что делает функция
метод `fizzbuzz(self, max_num)` класса `Fizz_Buzz` реализует классический вывод fizzbuzz для чисел от 1 до `max_num - 1`.
