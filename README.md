# DonkeyCar
Autonomous self-driving car using Autorope's donkeycar open-source software.

![donkeycar2](https://user-images.githubusercontent.com/87390731/133941557-80d9f9e6-2b96-49e0-ab23-7434410fb5fd.PNG)

## Software
The software was provided by the [autorope/donkeycar](https://github.com/autorope/donkeycar) repo and modified to suit the needs for my car. This software uses a convolutional neural network (CNN) to make predictions/decisions on how to drive the car based on users past driving input and camera images. You start by manually driving the car. The software records your driving inputs (steering angle and throttle) and camera images of the road. This data is fed to the CNN which produces a model of your driving habits. After you transfer that model onto the car and run autopilot which will infer the live visual data of the car on the track, or in other words, it will start driving on its own!
![image](https://user-images.githubusercontent.com/87390731/134260788-a8d13bc5-891f-414c-bb37-2fb63de9616f.png)

### Hardware
The Self-Driving RC Car uses components recommended by the donkeycar docs which consist of: a Jetson Nano, Host PC, gamepad, wide angle camera, PCA9685, ESC, Servo, and Brushed DC motor
![image](https://user-images.githubusercontent.com/87390731/134260487-38ae4370-b9de-4ff4-95b7-4f4d4c0c9972.png)

## Version 2 - Currently in the works
![IMG-2140](https://user-images.githubusercontent.com/87390731/133941502-43663ebd-376c-4e30-8b4d-c073a8fc3357.jpg)

## More Pictures
![donkeycar](https://user-images.githubusercontent.com/87390731/134261556-9fc5f617-20f4-4643-9629-a8bb6d5de349.PNG)
![donkeycar3](https://user-images.githubusercontent.com/87390731/134261551-da4c65b0-3be9-4bdc-842c-15f75c42ce79.PNG)
