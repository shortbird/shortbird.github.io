# Human Benchmark Aim Trainer Bot
Write a bot that gets record scores on the Aim Trainer game.

## Installation
Make sure the Pyautogui module is installed on your computer. Open Command Prompt and run this command:
```
pip install --user pyautogui
```

## Instructions
Write a Python bot that plays this Aim Trainer found [here.](https://humanbenchmark.com/tests/aim)
What's the fastest time your bot can get?

## Hints
* Find helpful hints for using Pyautogui [here.](https://pyautogui.readthedocs.io/en/latest/)
* The `pyautogui.locateCenterOnScreen()` function will be helpful here. You will need to take a screenshot of the target, then this function will search the screen for that exact image. This function returns the pixel coordinates of the center of the image, which you can then click using the `pyautogui.click()` function.
