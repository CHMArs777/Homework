# Homework
from random import randint
import time

def SIMVOL (start,end):
    password = ''
    for i in range (0, (randint (4,7)):
        password += chr(randint(start,end))
        return password

print (SIMVOL(65,122) +'_' +SIMVOL(48,57) + '_'+SIMVOL(58,64))
for k in range (10, 0, -1):
    print ('Осталось',k, 'секунд')
    time.sleep(1)
