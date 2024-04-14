# Лабораторная работа №5
# Включение семантики в анализатор. Создание внутренней формы представления программы.

## В качестве внутренней формы представления программы выберем Многоадресный код с явно именуемым результатом (тетрады)

## Цель работы: Дополнить анализатор, разработанный в рамках лабораторных работ, этапом формирования внутренней формы представления программы.

## Задание: Реализовать алгоритм записи арифметического выражения в виде тетрады.

## Примеры верных строк

a=b*-c+b*c;<br>
a=-g+a*h+-s/r;<br>
k=-g--f+-d*-c/-c+e;<br>

a=b*-(c+b)*c;<br>
a=-(g+a)*(h+-s)/r;<br>
k=(-g-(-f+-d)*-c)/-c+e;<br>


## Тестовые примеры

<img src="ex1.png" width=300px>
<img src="ex2.png" width=300px>
<img src="ex3.png" width=300px>
<img src="ex4.png" width=300px>
<img src="ex5.png" width=300px>
<img src="ex6.png" width=300px>

<img src="ex7.png" width=300px>
<img src="ex8.png" width=300px>
<img src="ex9.png" width=300px>
<img src="ex10.png" width=300px>
<img src="ex11.png" width=300px>
<img src="ex12.png" width=300px>
