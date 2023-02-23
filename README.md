# hand-control
This project aims to develop a tool to control various system features using only simple hand gestures.

## Brightness control
The first part of this project covers control over the brightness of the screen. By making a simple gesture, the project is alerted to either increase or decrease the screen brightness, and depending on the height of the fingers of the hand, the brightness is increased or decreased.

## How to run
For now, the way to run this project is through the Jupyter notebook. When you run the last cell, it will start using the webcam on your device, from that moment on you will be able to make the hand gestures to control the brightness. To finish the program you must stop the notebook.

### Hand pose
To control the brightness of the screen, you must have both the index and middle fingers extended and together while the other fingers should be folded. In this position, to increase or decrease the brightness, you must raise or lower the tip of the index or middle finger respectively.

### Requirements
Works only in Windows for now.

-numpy = 1.23.4

-mediapipe = 0.9.0.1

-screen-brightness-control = 0.17.0

-opencv = 4.6.0

#### Licensed under GNU GPLv3
