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
<img width="560" alt="diagram_lab_3" src="https://github.com/StudentNSTU/lab_5/assets/160150922/8326bb56-eecf-4c40-a8e7-49c9fa39200c">
<img width="617" alt="Снимок экрана 2024-04-15 в 12 54 03" src="https://github.com/StudentNSTU/lab_5/assets/160150922/2f3d7484-4b9a-422b-84da-df19ca529dc5">



   