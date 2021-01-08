
### Practice Questions:-

1. How can you trigger PyAutoGUI’s fail-safe to stop a program?

**Answers**
```
Move the mouse to the corner of the screen.
```
2. What function returns the current resolution()?

**Answers**

``` pyautogui.size() ```

3. What function returns the coordinates for the mouse cursor’s current position?

**Answers**

```pyautogui.position()```

4. What is the difference between pyautogui.moveTo() and pyautogui.move()?

**Answers**
```
pyautogui.moveTo() makes to move absolute coordinates of the screen and
pyautogui.move() moves to the position that is relative to the current position mouse. 
```
5. What functions can be used to drag the mouse?

**Answers**

```pyautogui.drag() and pyautogui.dragTo()```

6. What function call will type out the characters of "Hello, world!"?

**Answers**

```pyautogui.typewrite('Hello, world!')```

7. How can you do keypresses for special keys such as the keyboard’s left arrow key?

**Answers**

```pyautogui.press('left')```

8. How can you save the current contents of the screen to an image file named screenshot.png?

**Answers**

```pyautogui.screenshot('screenshot.png')```

9. What code would set a two-second pause after every PyAutoGUI function call?

**Answers**

```pyautogui.PAUSE = 2```

10. If you want to automate clicks and keystrokes inside a web browser, should you use PyAutoGUI or Selenium?

**Answers**
```
Selenium
```
11. What makes PyAutoGUI error-prone?

**Answers**
```
It clicks and types blindly hence it becomes difficult to find out whether its clicking on the correct window.
```
12. How can you find the size of every window on the screen that includes the text Notepad in its title?

**Answers**

```pyautogui.getWindowsWithTitle('Notepad')```

13. How can you make, say, the Firefox browser active and in front of every other window on the screen?

**Answers**

```
f = pyatuogui.getWindowsWithTitle('Firefox')
f.activate()
```