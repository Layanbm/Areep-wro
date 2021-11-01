

**Qualifying Round Programming**

•

•

This programming consists of two motors, an ultrasonic sensor, and a gyro sensor.

When the program starts, the first engine is looped forever to run at eighty percent

speed, and all angles are reset.

•

•

It will be repeated until the distance between the wall and the robot is less than

eighty-three centimeters, measuring is done using the Ultrasonic sensor.

In case that the distance becomes less than eighty-three centimeters, the gyro

sensor measures the angle. If it is equal to zero, then the robot is commanded to

wait for one part of a second, after which the engine completes running at eighty

percent speed.

•

•

•

•

If the gyro sensor measures the angle as greater than zero, it waits for a one part of

a second. Then, the second motor starts by turning five degrees at speed of eighty

percent, and then resets the angle again. In addition, this programming will be

repeated until the angle equals zero again. Then, stop the second motor and turn

negative five degrees at eighty percent speed by the first motor. And set the first

motor on eighty percent speed.

If the gyro sensor measures the angle as less than zero, it waits for a one part of a

second. Then, the second motor starts by turning negative five degrees at speed of

eighty percent, and then resets the angle again. In addition, this programming will

be repeated until the angle equals zero again. Then, stop the first motor and turn

negative five degrees at eighty percent speed by the second motor. And set the

second motor on eighty percent speed.

If the ultrasonic sensor measures the distance, and it is less than eighty-three, it

waits for one in ten seconds and then resets its angle. Then, the second motor

rotates negative twenty-five degrees at a speed of eighty percent, and when the

gyro sensor measures the angle and finds that it is greater than eighty degrees, it

waits for one in ten seconds. It stops the first engine and then revs the second

engine at twenty-nine degrees at a speed of eighty percent.

If the distance is not less than eighty-three degrees, the first motor is placed at a

speed of eighty percent.


