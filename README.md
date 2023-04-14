# Homework
#№1
found = 20
copym = 10
vor = 3
sber = ((copym * 365) + found) - vor * 52
print(sber)

#№2
age = int(input('Введи свой возраст и получи шутку:'))
if age == 10:
    print('- Что будет, если клюква наденет штаны? –Брюква!')
elif age == 11:
    print ('- Что скала зелёная виноградина синей? – Дыши!,Дыши!')
elif age == 12:
    print('Что сказал 0 цифре 8? – Привет, ребята!')
elif age == 13:
    print('Что такое сидит на потолке и хохочет? – Мухахохотуха!')
else:
    print ('Извини, на тебя шуток нет.')
    
 #№3
spisok =[]
spisok.append('Паучьи лапки')
spisok.append('Жабий палец')
spisok.append('Глаз тритона')
spisok.append('Крыло летучей мыши')
spisok.append('Жир слизня')
spisok.append('Кожа змеи')
print (mass[0])
print (mass[1])
print (mass[2])
print (mass[3])
print (mass[4])
print (mass[5])
def SpisokPokupok(tovar):
    print(tovar)
SpisokPokupok('Мандрагора')
SpisokPokupok('Болиголов')
SpisokPokupok('Болотный газ')

#№4
ves = int(input('Введите свой вес:'))
for i in range (0,15):
    lunves = ves * 0.165
    print('Ваш лунный вес во время', i, 'полета:', lunves, 'кг')
    ves +=1
#№5
banki = 500
bankivned = 2
ned = banki / bankivned
def KolichestvoBanok (bankivned):
    for i in range(0, 365):
        i +=1
        print('Расплющено банок в', i, 'неделю:', bankivned)
        bankivned += 2
        if bankivned >= 500:
            print('банки закончились')
            break
KolichestvoBanok(bankivned)

#№6
import turtle
turtle1 = turtle.Turtle()
turtle2 = turtle.Turtle()
turtle3 = turtle.Turtle()
turtle4 = turtle.Turtle()

turtle1.backward(200)
turtle1.forward(200)
turtle1.left(90)
turtle1.forward(100)
turtle1.right(90)
turtle1.forward(100)

turtle2.forward(20)
turtle2.left(90)
turtle2.forward(50)
turtle2.right(90)
turtle2.forward(50)

turtle3.forward(20)
turtle3.right(90)
turtle3.forward(50)
turtle3.left(90)
turtle3.forward(50)

turtle4.right(90)
turtle4.forward(100)
turtle4.left(90)
turtle4.forward(100)

turtle.exitonclick()
