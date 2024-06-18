Welcome to our web-based educational block-based programming environment for Arduino! This tool is designed to introduce K-12 students to the world of programming and electronics using the popular Arduino platform BlocklyDuino. Below are instructions on how to start the tool and an overview of its features:

## Getting Started:

1. Ensure you have a compatible web browser installed (Google Chrome, Mozilla Firefox, etc.).
2. Run this comment on terminal: python arduino_web_server.py so you can run a mini webserver that uses the Arduino IDE.
3. Navigate to http://127.0.0.1:8080/ on browser.
4. Start exploring.

### Arduino Setup
* Before you start coding keep in mind the Arduino should be setup as following:
*   ArduRookies Maze : Respect the following scheme to connect the Joystick to the Arduino.
   ![joystick](https://github.com/andreiispir/BlocklyDuino-gh-pages/blob/0523fc4cc70457aba5cf1424a2d307551fa90287/blockly/media/joystick.png)
*   ArduRookies Music: Make sure that the Blue button is connected to digital pin 7, Red Button to digital pin 8 and White button to digital pin 9. The piezo buzzer should have it's positive pin connected to digital pin 4. In the end your setups should look like this:
![Screenshot 2024-06-18 184407](https://github.com/andreiispir/BlocklyDuino-gh-pages/assets/147340167/ec4f813b-d27c-44ab-bb3e-efd0507aeaf5)


### Features

* Web-based educational block-based programming environment
* Programming Arduino with visually drag and drop code blocks
* Different sounds for different blocks as Interaction Technique(Everytime a block is placed on the workspace, a sound is played(click.mp3)). A different sound is played for every block.
* Generate fully compatible Arduino source code
* Upload code to Arduino board 
* High contrast, block and text dimensions as UI Technique for color blind children
* Additional dialogs for use cases.

### Usage
1. Open browser to BlocklyDuino, drag and drop blocks to make an Arduino program
2. Select the Arduino tab and press the Upload button. (press the Reset button to upload an empty program)
