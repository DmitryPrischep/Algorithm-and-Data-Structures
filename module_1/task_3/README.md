## Задание 1.3
# Очередь с динамическим буфером

Реализовать очередь с динамическим зацикленным буфером.

Обрабатывать команды push back и pop front.

## Формат ввода
В первой строке количество команд n. n ≤ 1000000.

Каждая команда задаётся как 2 целых числа: a b.

a = 2 - pop front

a = 3 - push back

Если дана команда pop front, то число b - ожидаемое значение. Если команда pop front вызвана для пустой структуры данных, то ожидается “-1”.

## Формат вывода
Требуется напечатать YES - если все ожидаемые значения совпали. Иначе, если хотя бы одно ожидание не оправдалось, то напечатать NO.

| Ввод  | Вывод |
| :---: | :-:   |
|  3    | YES   |
|  3 44    |       |
|  3 50    |       |
|  2 44    |       |