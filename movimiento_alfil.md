# Maqueen
# Imports go at the top
from microbit import *
from Maqueen import *

robot = Maqueen()

while True:
    if button_a.is_pressed():
        robot.set_motor(0,70)
        robot.set_motor(1,0)
        sleep(500)
        robot.mover_celda()
        robot.mover_celda()
        robot.mover_celda()
        robot.mover_celda()
        robot.mover_celda()
        robot.mover_celda()
        robot.mover_celda()
        robot.set_motor(70,0)
        robot.set_motor(0,1)
        sleep(500)
    if button_b.is_pressed():
         robot.set_motor(140,0)
         robot.set_motor(0,1)
         sleep(500)
         robot.mover_celda()
         robot.mover_celda()
         robot.mover_celda()
         robot.mover_celda()
         robot.mover_celda()
         robot.mover_celda()
         robot.mover_celda()
         robot.set_motor(0,70)
         robot.set_motor(1,0)
         sleep(500)
