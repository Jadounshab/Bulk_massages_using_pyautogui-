# Bulk_massages_using_pyautogui-
This Python script demonstrates an automated typing bot built using the PyAutoGUI library. The script allows you to simulate repetitive typing of a specific message followed by the "Enter" key press.
How it works:
The script imports the necessary modules, pyautogui for automation and time for adding delays.

It starts with a 4-second delay (time.sleep(4)) to give you enough time to switch to the desired application or platform where you want the messages to be typed.

The script then enters into a loop, executing the following steps 300 times (or any other specified number of times):

Uses pyautogui.typewrite("Chal Kal Milte h") to type the message "Chal Kal Milte h" (you can modify the message in the script as per your requirements).
Presses the "Enter" key using pyautogui.press("enter") to submit the message.
The loop continues until the count variable reaches 300, typing the message and pressing "Enter" each time.
