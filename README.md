# Info_lesson-56
1. цел, вещ лог сим лит byte shortint wold longint single real double extended
2. для оптимизации 
3. отличаеться тем что символьная переменная может хранит только 1 символ
4. логические данные иммет только 2 варианта да или нет
5. это порядок выпольнения, для назначения порядка
6. слева направо
7. для назначение приоретета
8. иногда автоматически приводит тип к более "широкому"
9. для получение целого и остатка
10. в различии в реализации операторов mod и % в разных языках
11. обычно используеться "**"
12. abs(x), sqrt(x), sin(x), cos(x), exp(x), in(x), trunc(x) round(x)
13. обычно использует round(x)
14. это числа которые были сгенерированы , чтобы результат был разным
15. это числа которые вычисляются по какой-то формуле, результат будет предсказуемым
16. случайные числа не предсказуемые в от личия естетвенное случайное число
17. rand() random()



Задачи 
1. в Си -3.4Е+38 до 3.4Е+38
2. Паскале:
      program Calculate; var a, b, c: integer; sum, product, average: real; begin writeln('Введите три целых числа:'); readln(a, b, c);

      sum := a + b + c; product := a * b * c; average := sum / 3;

      writeln(a, ' + ', b, ' + ', c, ' = ', sum:0:0); writeln(a, ' * ', b, ' * ', c, ' = ', product:0:0); writeln('Среднее арифметическое = ', average:0:6); end.

3.    program CircleCalculator; const Pi = 3.14159265359; var radius: real; area, circumference: real; begin writeln('Введите радиус круга:'); readln(radius);
      area := Pi * radius * radius; circumference := 2 * Pi * radius;

      writeln('Площадь круга: ', area:0:2); writeln('Длина окружности: ', circumference:0:2); end

4.   program SwapVariables; var x, y, temp: integer; begin writeln('Введите два целых числа:'); readln(x, y);
     temp := x; x := y; y := temp;

      writeln('После обмена: x = ', x, ', y = ', y); end.


5. program SwapWithoutTemp; var x, y: integer; begin writeln('Введите два целых числа:'); readln(x, y);
    x := x + y; y := x - y; x := x - y;

    writeln('После обмена: x = ', x, ', y = ', y); end.

6.  program PowerOfTen; var x, i, result: integer; begin writeln('Введите число:'); readln(x);
    result := 1; for i := 1 to 10 do result := result * x;
  
    writeln(x, ' в степени 10 = ', result); end.

7. c := a + 1/3; // а writeln(c);

  c := a + 4/2*3 + 6; // б writeln(c);

  c := (a + 4)/2*3; // в writeln(c);

  c := (a + 4)/(b + 3) * a; // г writeln(c); end.

8.  c := (a mod b) + b; // a) writeln(c);

    c := (a div b) + a; // b) writeln(c)

9. Для вычислений с a=-22 и b=-4 результаты могут отличаться в зависимости от обработки отрицательных чисел в разных языках. В Паскале операции div и mod могут дать неожиданные результаты.
10. program SplitNumber; var num, hundreds, tens, units: integer; begin writeln('Введите трехзначное число:'); readln(num);

    hundreds := num div 100; tens := (num div 10) mod 10; units := num mod 10;

    writeln(hundreds, ',', tens, ',', units); end.

11. program DistanceBetweenPoints; var point1, point2, distance: integer; begin writeln('Введите координаты двух точек:'); readln(point1, point2);
    if point1 > point2 then distance := point1 - point2 else distance := point2 - point1;

    writeln('Расстояние между точками: ', distance); end

12. result := x * y; writeln('Произведение: ', result:0:2); end
13. writeln('Округленное число: ', round(number)); end
14. Randomize; for i := 1 to 5 do begin randomNum := Random(b - a + 1) + a; writeln(randomNum); end; end
15. writeln('Сумма кубиков: ', sum); end.
16. if N < 2 then begin writeln('Количество учеников должно быть не менее 2.'); exit; end;
17. if a >= b then begin writeln('Ошибка: a должно быть меньше b.'); exit; end
