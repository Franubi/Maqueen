# Maqueen
from microbit import *
from MaQueen import *

robot = Maqueen()


while True:
    if button_a.was_pressed():
        robot.mover_celda()
    if button_b.was_pressed():
         robot.mover_celda()
         robot.mover_celda()
