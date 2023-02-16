# Homework
a = int(input('Введите номинал:'))
if a == 1:
    print('Джордж Вашингтон')
elif a == 2:
        print('Томас Джефферсон')
elif a == 5:
        print('Авраам Линкольн')
elif a == 1:
        print('Джордж Вашингтон')
elif a == 10:
        print('Александр Гамильтон')
elif a == 20:
        print('Эндрю Джексон')
elif a == 50:
        print('Улисс Грант')
elif a == 100:
        print('Бенджамин Франклин')
else:
    print('ERROR!!!')




kletka = str(input('Введите клетку на доске:'))
if (kletka[0] == 'a' or kletka[0] == 'c' or kletka[0] == 'e' or kletka[0] == 'g') and (kletka[1] == '1' or kletka[1] == '3' or kletka[1] == '5' or kletka[1] == '7'):
    print ('Черное')
elif (kletka[0] == 'b' or kletka[0] == 'd' or kletka[0] == 'f' or kletka[0] == 'h') and (kletka[1] == '2' or kletka[1] == '4' or kletka[1] == '6' or kletka[1] == '8'):
    print ('Черное')
else:
    print('Белое')
