import pyautogui as pyg

speed = 0.096 #0.96 best
a,b = 403,355
px,py = pyg.locateCenterOnScreen('playButton.png')
pyg.moveTo(px,py)
pyg.click()
print "[*] Crackatoa Simple Lumberjack Bot "
print "[*] Starting lumberjack "
print "[*] Bot Running "
print "[*] Press Ctrl + c to stop "

while True:
    tree = pyg.pixel(a,b-35)
    if tree == (161, 116, 56):
        pyg.typewrite(['left', 'left'], speed)
    else:
        pyg.typewrite(['right', 'right'], speed)
