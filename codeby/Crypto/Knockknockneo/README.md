# Тук-тук, Нео

[Тук-тук, Нео](https://codeby.games/categories/cryptography/362168b2-b1d5-4477-9a0f-cebb128ae9a6)

## Описание задания
Нео получил загадочное послание и должен его разгадать. Эти цифры скрывают в себе глубокий секрет, который откроется лишь тем, кто способен разглядеть в них нечто больше

Формат флага: CODEBY{flag}

## Решение

В прикрепленном к заданию файле видим текст следующего содержания:

```
3x12
^2/4, 2/5, 3/12, 3/1,  2/4, ^2/4, 2/5, 3/12, 3/1,  2/4, ^2/5,  2/10, 3/5, ^2/8, 1/1, 2/4, 2/10, ^3/7, 1/6
```

Первое что брасается в глаза это ```3x12```, допустим что это 3 столбца и 12 строк. Теперь все это нужно чем то заполнить - возьмем английский алфавит и цифры от 0 до 9. В итоге получится

```
a b c
d e f
g h i
j k l
m n o
p q r
s t u
v w x
y z 1
2 3 4
5 6 7
8 9 0
```

Теперь осталось дело за малым сопоставить столбец и строку, ну и найти нужную букву или цифру к примеру ```^2/4 = K```, также не забываем про ```^``` - верхний регистр

Собираем флаг в одно целое, сдаём и да не обращаем внимание на пробелы ```^2/4, 2/5, 3/12, 3/1,  ``` )))
