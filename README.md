# -3
Just another repository
myList = input("Введите список чисел через пробел: ").split()
print("Наибольшее число в списке - {}".format(max(myList)))
x = [1, 6, -3, 7]
max = x[0]
for el in x:
    if el > max:
        max = el

for i in range(len(x)):
    if x[i] > max:
        max = x[i]
