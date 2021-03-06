# Училище

## Условие
Иванчо не обича училището (като вас). Той живее в квартал с **N** на брой сгради. Номера на неговата къща е номер **X**, а на училището му номер **Y**. Има **M** пътя между сгради, по които Иванчо може да мине напът за училище. Разбира се, той иска да се забави колкото се може повече. За съжаление ако съседите го видят, че е спрял, ходи по-бавно или върви в грешната посока, ще кажат на майка му.

## Вход
- От първия ред се четат 4 числа - **N**, **M**, **X**, **Y**
- От следващите **M** реда се четат по 3 числа
  - **A**, **B**, **T** - Иванчо може да стигне от сграда **A** до сграда **B** за **T** минути

## Изход
- Да се изведе за колко най-много време Иванчо може да стигне до училище без някой съсед да говори с майка му

## Ограничения
- 1 <= **N** <= 500
- Лимит за памет: **16 MiB**
- Лимит за време: **0.2 секунди**

## Примери

### Вход
```
5 9 2 1
2 3 63
2 1 33
4 5 44
1 3 88
4 1 48
5 1 91
2 5 85
4 3 7
2 4 12
```

### Изход
```
176
```

### Вход
```
10 20 6 2
10 3 36
7 2 86
10 7 15
5 7 53
6 9 80
7 4 92
5 4 46
1 3 85
1 8 1
9 3 97
8 4 44
8 7 16
6 4 76
1 9 3
2 4 3
7 3 54
10 4 83
9 8 79
5 8 86
2 3 95
```

### Изход
```
261
```

### Вход
```
10 30 5 7
3 4 99
8 9 28
1 9 90
10 7 47
4 6 61
3 2 59
2 4 67
10 8 24
6 9 22
1 6 81
2 5 26
3 9 9
4 5 17
2 7 95
1 7 77
3 10 33
5 1 6
4 1 16
3 5 13
6 7 58
2 10 44
3 8 36
2 1 83
2 9 63
5 9 75
3 1 6
4 7 84
5 10 28
5 6 54
4 8 25
```

### Изход
```
145
```
