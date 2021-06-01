from pyautogui import *
import pyautogui
import keyboard
import random
import win32api, win32con
import time

#tile 1 X:  378 Y:  340 RGB: (  0,   0,   0)
#tile 2 X:  448 Y:  340 RGB: ( 85,  87, 117)
#tile 3 X:  525 Y:  340 RGB: ( 88,  91, 117)
#tile 4 X:  588 Y:  340 RGB: ( 82,  84, 116)

def click(x,y):
    win32api.SetCursorPos((x,y))
    win32api.mouse_event(win32con.MOUSEEVENTF_LEFTDOWN,0,0)
    time.sleep(0.01) #Pause 0.01 sec
    win32api.mouse_event(win32con.MOUSEEVENTF_LEFTUP,0,0)

while keyboard.is_pressed('q')== False:
    if pyautogui.pixel(378,250) == (0,0,0): #แถว1
        click(378,250)
    if pyautogui.pixel(448,250) == (0,0,0): #แถว2
        click(448,250)
    if pyautogui.pixel(525,250) == (0,0,0): #แถว3
        click(525,250)
    if pyautogui.pixel(588,250) == (0,0,0): #แถว4
        click(588,250)
