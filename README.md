# CLEVR0.O
# Abstract
  In big restaurants often transferring the prepared food to the consumers becomes difficult for waiters at peak hours. We aim to deploy an automated waiter bot which can transfer the content placed in it, to a specified table. This will save the number of waiters needed for the job and will reserve waiters for more complex queries of the customers and moreover it will streamline the process of giving and delivering the order within the building.
  The same bot can be deployed in offices to deliver the requested snacks to a specified cubicle and also can transfer hard copies of files from the requested cubicle(source) to the destination cubicle 
(destination), which in turn will save much time of the employees.

**1.	The Robot waiter will work on the phenomenon of line following** : Bot will use 3 IR sensor; one IR at the centre will set the robot waiter on line while the other 2 will help the bot to trace the line and count the junction (J1, J2etc) to reach the proper destination. 

**2.	The processing of address of tables/cubicles will be done on NODEMCU:** All the processing of the input signals and expected action will be controlled by NodeMcu microcontroller to which these IR sensors will be connected, facilitating the movement of bot. NodeMcu has Wi-Fi module built inside it which helps it to connect to internet and help us explore the IoT (Internet of Things) part of our bot.

**3.	Movement Track:** Every Table/Cubicle inside the restaurant/office will be marked with a junction on the route line (route line is nothing but a black line to guide the bot). 

**4.	Communicating to the bot:** NodeMcu is coded with a built-in response website which will be displayed on the accessing device (smartphone, pc) when it will try to access the microcontroller through its IP address on any browser.Through the response website people will give command to come to its junction which the bot will acknowledge and come to its designated place autonomously. 

**5.  User-friendly:** The response website could be customised according to our need. For example, it will serve as a waiter in a restaurant but can act as a clerk in an IT sector office. Furthermore for even better interaction of the bot with the daily world we will put an ultrasound sensor on the front of the bot which will help it to know whether the route is obstacle free; if a person is standing on the route as the route is all inside the office then the bot will simply go in a pause state when it finds obstacle in its path and be fitted with a buzzer if the obstacle is not removed within a specific period of time like 5 seconds.
