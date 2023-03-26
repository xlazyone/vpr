# Лабораторная работа #4

## Материалы

* [Методические указания I семестр.doc](../%D0%9C%D0%B5%D1%82%D0%BE%D0%B4%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B8%D0%B5%20%D1%83%D0%BA%D0%B0%D0%B7%D0%B0%D0%BD%D0%B8%D1%8F%20I%20%D1%81%D0%B5%D0%BC%D0%B5%D1%81%D1%82%D1%80.doc)

## Варианты заданий
Дан массив из десяти знаковых чисел (слов или байт). Требуется:

1.	Дан массив из 10 байт. Посчитать количество байт, в которых сброшены 6 и 4 биты.
2.	Дан массив из 8 байт. Рассматривая его, как массив из 64 бит, посчитать количество единиц.
3.	Дан массив из 8 байт. Рассматривая его как массив логических значений х0 х1 х2 х3 х4 х5 х6 х7 (true-есть ненулевые биты в байте, false-все биты нулевые), вычислить логическую формулу 
`f=(x7 & x6 & x1) V (x6 & x4 & x2 & x1 & x0) V (x7 & x6 & x3 & x1).`
4.	Дан массив из 10 байт. Посчитать количество байт с числом единиц в байте равным три.
5.	Рассматривая байт как набор логических значений x7 x6 x5 x4 x3 x1 x0 (true -1, false - 0), вычислить логическую формулу
`f=(x7 & x6 & x3 ) V (x6 & x4 & x2 & x1) V (x7 & x6 & x2 & x0)`
6.	Дан массив из 8 байт. Рассматривая его, как массив из 64 бит посчитать длину самой длинной последовательности единиц.
7.	Дан массив из 10 байт. Посчитать количество единиц во всех разрядах, кратных трём: 3, 6, 9, …, 75, 78.
8.	Дан массив из 5 байт. Рассматривая его как массив из 8 пятиразрядных слов,  найти “исключающее или” всех 8 слов для выражения “10101”.
9.	Дан массив из 6 байт. Рассматривая его, как массив из 48 бит, посчитать в нём количество нулей. 
10.	Дан массив из 8 байт. Рассматривая его, как массив из 64 бит, посчитать количество пар единиц в окружении нулей. Конец последовательности рассматривать как нуль.
11.	Дан массив из 7 байт. Рассматривая его, как массив из восьми семибитных слов, посчитать количество слов с нечетным числом нулей в слове.
12.	Дан массив из 9 байт. Рассматривая его как массив из 72 бит, посчитать число переходов между нулями и единицами.
13.	Дан массив из 3 байт. Рассматривая его, как массив из 24 бит, посчитать количество одиночных единиц в окружении нулей. Конец последовательности рассматривать как нуль.
14.	Дан массив из 6 байт. Посчитать количество байт число единиц, в которых не превышает 3.
15.	Дан массив из 11 байт. Посчитать количество байт, в которых нет единиц, стоящих рядом.
16.	Дан массив из 4 байт. Рассматривая его, как массив из 32 бит посчитать длину самой длинной последовательности нулей.
17.	Дан массив из 6 байт. Посчитать количество единиц во всех разрядах, кратных пяти: 5, 10,  …, 45.
18.	Дан массив из 3 байт. Рассматривая его как массив из 8 трёхразрядных слов,  найти “исключающее или” всех 8 слов для выражения “101”.
19.	Дан массив из 7 байт. Рассматривая его, как массив из 56 бит, посчитать в нём количество нулей, стоящих после единицы. Конец последовательности рассматривать как нуль. 
20.	Дан массив из 8 байт. Рассматривая его, как массив из 64 бит, посчитать количество пар единиц в окружении нулей. Конец последовательности рассматривать как нуль.
21.	Дан массив из 5 байт. Рассматривая его, как массив из восьми пятибитных слов, посчитать количество слов с чётным числом единиц в слове.
22.	Дан массив из 6 байт. Рассматривая его, как массив из 48 бит, посчитать число двух единиц, стоящих между нулями. Конец и начало последовательности рассматривать как нули.
23.	Дан массив из 3 байт. Рассматривая его, как массив из 24 бит, посчитать количество одиночных единиц в окружении нулей. Конец последовательности рассматривать как нуль.
24.	Дан массив из 6 байт. Посчитать количество байт, число единиц в которых не превышает 3.
25.	Дан массив из 11 байт. Посчитать количество байт, в которых нет единиц, стоящих рядом.


## Работа
##### Вариант 2: Дан массив из 8 байт. Рассматривая его, как массив из 64 бит, посчитать количество единиц.
```asm

```

## Вопросы

1.	В чем отличие команд test и and?
2.	Как сбросить 5-й бит переменной байта ВВ?
3.	Как установить 5-й бит переменной байта ВВ?
4.	Как инвертировать 5-й бит переменной байта ВВ?
5.	Как проверить установлен ли 5-й бит переменной байта ВВ?
6.	Как проверить четным или нечетным является количество уста¬нов¬лен-ных бит в байте?
7.	Какие флаги условий модифицируются после выполнения команд and, or, xor ?
8.	В чем основное отличие команд логических и арифметических сдвигов?
9.	Укажите максимальное число двоичных разрядов, на которые можно сдвинуть операнд с помощью одной команды сдвига?


*Авторство: **Бояршинов Н.О***