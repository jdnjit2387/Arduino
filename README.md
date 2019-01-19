# Arduino Project - Drive Assist System

The project uses Arduino microprocessor(available on Amazon) and motor driver circuit(L293D)
The software interfaces used is C, Arduino IDE, Processing 3.0 Interface 

 Parking assist: - It assists the driver to park the car without accidents. It safely parks the car in between two other vehicles. This helps the driver as he doesn’t have to painstakingly maneuver the car each time. It also helps avoid possible collisions. 
 Power Optimizations: - It automatically distributes the battery power efficiently among the four wheels to provide maximum speed and torque depending on the situations. This will help minimize the power/fuel consumptions when not required in full capacity. When the car is on a straight road it need not need all the 4 wheels. But on a steep hill or on sand 4 wheel drive will be required. 
 Collision Detection: - It stops the vehicle when a pedestrian, another vehicle or an obstacle is detected by the sensor. The ultrasonic sensors in the front and back measure the distance between the vehicle and other objects and stops the vehicles once the distance is less than the minimum distance. 
 Password protection: - It will not start the vehicle unless the user enters correct password, hence, providing an authorization program. The password provided is unique to the user and will not activate the system if a wrong password is entered. This is a very useful feature as this will prevent unauthorized use. This also ensures that children do not access the system. 
Drive Assist System   
 Highway Safety: - This feature aligns the vehicle to a particular lane and hence prevents the vehicle from accidentally moving into other lanes. This feature is very useful in case of drunken driving. This will prevent collisions as the vehicle will continue to move in the same lane and also obstacle detection feature prevents the vehicle from colliding with objects, pedestrian, walls and other such objects. 

Some of the features of the Drive-Assist System like parking assist and highway safety have been implemented in high-end automobiles like Audi and BMW.  These features automate the vehicles and give a comfortable driving experience. But these automated features makes the vehicle expensive. Our project aims to implement these features in low-end automobiles. 
 
The project uses distance sensors and IR sensors for implementing its various features like parking assist, highway safety, collision detection and pedestrian detection. We have written algorithms for each of the features that helps the vehicle steer so as to implement that particular feature. For parking assist there will be a side sensor that once if it detects a vacant spot the vehicle will steer towards the vacant spot. In highway safety, if both the IR sensors are on the white space it moves forward. If one of the sensors goes on the black line the vehicle will adjust so as to keep in track. In collision detection/pedestrian detection if the distance sensor detects any object it will stop immediately.                      


