# Лабораторная работа №5
### Включение семантики в анализатор. Создание внутренней формы представления программы.
Цель работы: Дополнить анализатор, разработанный в рамках лабораторных работ, этапом формирования внутренней формы представления программы.

Задание: Реализовать алгоритм записи арифметического выражения в виде тетрады.


1) Дополнить парсер грамматикой G[<АВ>]. Реализовать данную КС-граммматику методом рекурсивного спуска:
```
E → TA

A → ε | + TA | - TA

T → ОВ

В → ε | *ОВ | /ОВ

О → id | (E)
```
2) Реализовать алгоритм записи выражений в форме тетрад.

## Примеры верных строк

```
m=(k+s)*c*e;
y=s-(v+d)-h;
z=((e-n)/d*s)*p;
```

## Скриншоты работы программы 
<img width="618" alt="Снимок экрана 2024-04-15 в 12 51 22" src="https://github.com/StudentNSTU/lab_5/assets/160150922/5aa11975-440f-43ef-a3e7-712d9aa42cbb">
<img width="619" alt="Снимок экрана 2024-04-15 в 13 01 57" src="https://github.com/StudentNSTU/lab_5/assets/160150922/ef5b4c40-51e4-4522-9028-eb6cc9f6d733">
<img width="617" alt="Снимок экрана 2024-04-15 в 12 54 03" src="https://github.com/StudentNSTU/lab_5/assets/160150922/2f3d7484-4b9a-422b-84da-df19ca529dc5">



   
