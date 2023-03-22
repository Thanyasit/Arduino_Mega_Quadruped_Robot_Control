# Arduino Mega Quadruped Robot Control
## Description:
This program controls a robot using four servos and an ultrasonic sensor. It was developed for a competition using an Arduino Mega board.

The robot's movement is controlled by changing the position of its four servos. The code includes predefined positions for standing, walking, climbing, and other movements. These positions are stored in arrays, such as <b>'stand'</b>, <b>'M1'</b>, <b>'M2'</b>, etc. You can modify these arrays or add new ones to create custom movements for your robot.

The ultrasonic sensor is used to detect obstacles and prevent the robot from colliding with them. The code includes functions to read the sensor's data and calculate the distance to the nearest obstacle. If an obstacle is detected, the robot stops and waits for a few milliseconds before continuing its movement.

Developed from [Quadruped_Robot_Control](https://github.com/Thanyasit/Quadruped_Robot_Control) for ABU Robot Contest Thailand Championship 2019

## Hardware Requirements
- Arduino Mega board
- Two servos for each leg
- Ultrasonic sensor

## Installation
1. Download or clone this repository to your computer.
2. Open the <b>'Arduino_Mega_Quadruped_Robot_Control'</b>file using the Arduino IDE.
3. Connect your Arduino Mega board to your computer using a USB cable.
4. Select the correct board and port from the Tools menu.
5. Upload the code to your Arduino board.

## Usage:
1. Connect the servos and ultrasonic sensor to your Arduino board.
2. Power on the robot and wait for it to initialize.
3. Place the robot in an open space with no obstacles.
4. Use the remote control to start the robot's movement.
5. The robot will start walking and avoiding obstacles using its ultrasonic sensor.

## Code:
The code includes predefined positions for the legs that are defined as arrays. The user can modify these arrays to adjust the position of the legs. The code uses the Servo library to control the servo motors, and each leg is controlled by two servo motors.

The main function of the code is to move the legs of the robot in a coordinated way to achieve walking and climbing movements. The code also includes a function to make the robot stand still.

## License

This program is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
