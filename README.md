# Hand-Gesture-Controlled-Robot-with-Face-Detection-and-Recognition-Capabilities <br><br>

In this paper, we introduced an accelerometer (ADXL335) based Gesture controlled Robot with ATmega16 microcontroller having face detection and recognition capabilities. Here, the ADXL335 accelerometer sensor act as the input device which is mounted on the hand, ATmega16 microcontroller act as the processing unit, DC Motor Driver act as the driver for the motors connected to the Robot, and RF link acts as a channel for wireless communication. The ATmega16 microcontroller reads the analog output values(x and y-axis values of the accelerometer, z-axis value left, as it is not needed in this paper) of the ADXL335 accelerometer sensor and converts that analog values to digital values with its analog to digital converter. Face detection and Recognition begins with extracting the coordinates of
features such as width of mouth, width of eyes, pupil, and compare the result with the measurements stored in the database and return the closest record (facial metrics). Face Recognition and Detection would be done using Principle Component Analysis Method. A camera will be mounted on the top of our main unit of the robot. The camera of our robot and the computer on which live steaming will be played will be connected to the same Wi-Fi connection. This robot will help in various application such as security of a place, attendance system etc.<br><br>

## Schematic Diagram <br><br>

### Reciever module <br><br>

![](./images/Rm_module.PNG)<br><br>

### Transmitter module <br><br>

![](./images/Tm_module.PNG)<br><br>

## Prototype <br><br>

![](./images/robot.PNG)<br><br>

## Face detection and Recognition Application <br><br>

### Database creation <br><br>

![](./images/Cr_database.PNG)

### Face Recognition

![](./images/di_database.PNG)

## Url

- https://ieeexplore.ieee.org/document/8269666<br><br>

### Contributors

- Aman Budhraja, Akshit Sharma, Shantanu Malhotra, Saurabh Deswal
