RobotSensorLibrary
==================

A library that allows for easy interfacing with the robot sensors.

# RobotMovementLibrary

A library providing functions that allow for robot movement. This includes forwa
rd movement, backward movement, and left/right turns.

## Functions

- `void initializePinOuts()`
        - Sets the proper pins as output and associates them with their correspo
	nding clocks.
- `void configureTimer()`
        - Configures the timers so that the duty cycle is 50% when set/reset mod
	e is used, and inializes all TACCTL's to 101 or reset mode.

- `void leftMotorBackward()
	- Moves the left motor backward, this function is hidden from the user.

- `void leftMotorForward()`
        - Moves the left motor forward, this function is hidden from the user.

- `void rightMotorBackward()`
        - Moves the right motor backward, this function is hidden from the user.


										## Example Code
										```c
										        // here is some code
											        initializePinOuts();
										'''
