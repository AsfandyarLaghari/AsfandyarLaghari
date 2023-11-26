import pyautogui as pag
import random
import time
while True:

    x = random.randint(200, 210)
    y = random.randint(450, 600)
    pag.moveTo(x, y, 0.5)
    pag.click(button = 'right')
    time.sleep(2)
