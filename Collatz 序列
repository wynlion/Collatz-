# -*- coding: UTF-8 -*-
# Collatz 序列
def collatz():
    global number
    if number % 2 == 0:
        print(number // 2)
        number = number // 2
    else:
        print(3*number + 1)
        number = 3*number + 1
number = int(input('Enter number:'))
while True:
    if number != 1:
        collatz()
    else:
        break
