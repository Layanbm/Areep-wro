

Qualifying Round Programming

•

This programming consists of two motors, an ultrasonic sensor, and a gyro sensor.

•

When the program starts, the first engine is looped forever to run at eighty percent

speed, and all angles are reset.

•

It will be repeated until the distance between the wall and the robot is less than

eighty-three centimeters, measuring is done using the Ultrasonic sensor.

•

In case that the distance becomes less than eighty-three centimeters, the gyro

sensor measures the angle. If it is equal to zero, then the robot is commanded to wait for

one-tenth of a second, after which the engine completes running at eighty percent speed.

•

If the gyro sensor measures the angle as greater than zero, it waits for one-tenth of

a second. Then, the second motor starts by turning five degrees at speed of eighty percent

and then resets the angle again. In addition, this programming will be repeated until the

angle equals zero again. Then, stop the second motor and turn negative five degrees at

eighty percent speed by the first motor. And set the first motor on eighty percent speed.

•

If the gyro sensor measures the angle as less than zero, it waits for one-tenth of a

second. Then, the second motor starts by turning negative five degrees at speed of eighty

percent and then resets the angle again. In addition, this programming will be repeated until

the angle equals zero again. Then, stop the first motor and turn negative five degrees at

eighty percent speed by the second motor. And set the second motor on eighty percent

speed.

•

If the ultrasonic sensor measures the distance, and it is less than eighty-three, it

waits for one-tenth of a second and then resets its angle. Then, the second motor rotates

negative twenty-five degrees at a speed of eighty percent, and when the gyro sensor

measures the angle and finds that it is greater than eighty degrees, it waits for one-tenth of

a second. It stops the first engine and then revs the second engine at twenty-nine degrees at

a speed of eighty percent.

•

If the distance is not less than eighty-three degrees, the first motor is placed at a

speed of eighty percent.

Traffic lights programming

We made two different programs for this stage, one of which is based on the color sensor,

and the other is based on rotations. This is since our color sensor is poorly effective, it will

cause a problem with the performance of the robot, so we made a workaround by using

rotation.

\* This programming consists of two motors and a color sensor.

\* When the program starts, the first motor of negative one hundred and eighty degrees is

running at thirty percent.

\* In case that the color sensor detects a red (orange) color, the second motor rotates at

negative forty degrees at a speed of thirty percent, and then rotates a one and a half





rotation at a speed of thirty percent. Then it waits for one-tenth of a second, after which the

second engine revs eighty degrees at a speed of thirty percent and the first motor rotates a

one and seven out of ten rotation at speed of thirty percent. Then, The second motor

rotates at negative forty degrees at a speed of seventy-five percent, and the first motor

completes half its rotation at a speed of thirty percent.

\* If the color sensor detects a green color, the first motor runs at one hundred and eighty

degrees at a speed of thirty percent and then rotates -by the second motor- forty degrees at

a speed of thirty percent, and it runs one and a half rotations -by the first motor-. Then it

waits for one-tenth of a second. Moreover, the second motor rotates negative eighty

degrees at a speed of thirty percent, the first motor runs one and seven out of ten rotations

at a speed of thirty percent, the second motor rotates forty degrees at a speed of seventy-

five percent.

The final programming

This programming works as the wave method, and it is the second programming that we did

without the color sensor, just by rotating.

\* This programming consists of two motors.

\* The first motor is “c” and it stands for running the robot, and the second motor is “d” and

it stands for rotating with the steering wheel.

\* The motor “d” rotates for thirty-two degrees at a speed of seventy-five percent.

\* The motor “c” runs for two rotations at a speed of seventy-five percent.

\* The motor “d” rotates for negative sixty degrees at a speed of seventy-five percent.

\* The motor “c” runs for sex rotations at a speed of seventy-five percent.

\* The motor “d” rotates for forty-one degrees at a speed of seventy-five percent.

\* The motor “c” runs for four and five parts of ten rotations at a speed of seventy-five

percent.

\* The motor “d” rotates for negative forty degrees at a speed of seventy-five percent.

\* The motor “c” runs for one rotation at a speed of seventy-five percent.

\* The motor “d” rotates for twenty degrees at a speed of seventy-five percent.

\* The motor “c” runs for four and seven parts of ten rotations at a speed of seventy-five

percent.

\* The motor “d” rotates for negative twenty-three degrees at a speed of seventy-five

percent.

\* The motor “c” runs for half a rotation at a speed of seventy-five percent.

\* The motor “d” rotates for eight degrees at a speed of seventy-five percent.





\* The motor “c” runs for four and three parts of ten rotations at a speed of seventy-five

percent.

\* The motor “d” rotates for forty degrees at a speed of seventy-five percent.

\* The motor “c” runs for five and two parts of ten rotations at a speed of seventy-five

percent.

\* The motor “d” rotates for negative forty-eight degrees at a speed of seventy-five percent.

\* The motor “c” runs for seven rotations at a speed of seventy-five percent.

\* The motor “d” rotates for forty-seven degrees at a speed of seventy-five percent.

\* The motor “c” runs for six rotations at a speed of seventy-five percent.


