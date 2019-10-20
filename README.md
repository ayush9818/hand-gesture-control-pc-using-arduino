# hand-gesture-control-pc-using-arduino

Dependencies:

1) pyautogui : pip install pyautogui

2) serial : pip install serial

Hardware Used:

1) Arduino 

2) Two UltraSonic Sensors

Contents:

1) main.py : Python file that receives data from ultrasonic sensor via arduino through ultrasonic sensor

2) arduino_control/pc_auto.ino : Arduino file that interacts with ultrasonic sensor

Features : 

1) Play / Pause : When both hands are detected

2) Rewind : When only left hand is detected

3) Forward : When only right hand is detected

4) Volume Up/Down : Motion of right hand forward and backward

