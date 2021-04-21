# Faculty-Evaluator--IUB
import pyautogui
print(pyautogui.position())

base_x = 1265
base_y = 623
Q1_option_3 = 737
Q2_y = 666

#Question 1 (works)
pyautogui.click(base_x, base_y) #goes to 1st question and open drag downs
pyautogui.click(base_x, Q1_option_3) #goes to 1st's 3rd option

#rest of the Questions

count = 0
#ok till 10
while count < 14:
    count += 1
    pyautogui.move(0, -71) # goes to q2
    pyautogui.click() # open drop down
    pyautogui.move(0, 114)
    pyautogui.click()

pyautogui.moveTo(x =918, y = 820)
