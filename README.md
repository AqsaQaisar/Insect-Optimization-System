𝐈𝐧𝐬𝐞𝐜𝐭 𝐎𝐩𝐭𝐢𝐦𝐢𝐳𝐚𝐭𝐢𝐨𝐧 𝐒𝐲𝐬𝐭𝐞𝐦

This project is all about automatic pest detection system.This project is used to avoid hurdles in robot car way it automatically moves away when detect a hurdle, and had a mop that is used to clean where the dust is detected.

𝐂𝐨𝐧𝐭𝐞𝐱𝐭

『1』Introduction

『2』Circuit diagram

『3』Scope

『4』Code

『5』Demonstration

『6』Requirements

𝐈𝐧𝐭𝐫𝐨𝐝𝐮𝐜𝐭𝐢𝐨𝐧

A car charge with solar energy and by using actuator it automatically detects a pest and used a pest spray attach to car to remove and kill pests.
The sensor used in project is high power thermal sensor to detect spectral reflection caused by grass to detect a pest or extra weed. We also used a low power camera to record a surface for further action and send it to centralized platform automatically. 
An optical camera capture images of grass land and then compare it with existing images of a healthy leaves taken for result testing. Change in chlorophyll patterns indicates the presence of weeds or pests. 
The data collected through these sensors is quickly transferred to a centralized platform wirelessly.
A farmer can monitor the health of its crop form distant locations and protect it from the attack of pesticides and harmful herbs and weeds.Remote pest monitoring has radically reduced offline inspection and random field visits.

𝐜𝐢𝐫𝐜𝐮𝐢𝐭 𝐃𝐢𝐚𝐠𝐫𝐚𝐦

After assembling the robot chassis, you can wire the circuit by following the next schematic diagram.
![image](https://user-images.githubusercontent.com/126898862/222795510-570fd972-9b4e-4317-892c-8b6db89ca3eb.png)
Start by connecting the ESP32-CAM to the motor driver as shown in the schematic diagram. You can either use a mini breadboard or a stripboard to place your ESP32-CAM and build the circuit.
We assembled all the connections on a mini stripboard as shown below.

![image](https://user-images.githubusercontent.com/126898862/222800360-c3fbe924-1905-45e7-b0c3-4c116afafaed.png)
𝓝𝓸𝓽𝓮 we suggest soldering a 0.1 uF ceramic capacitor to the positive and negative terminals of each motor, as shown in the diagram to help smooth out any voltage spikes. Additionally, you can solder a slider switch to the red wire that comes from the power bank. This way, you can turn the power on and off.

Finally, apply power with a power bank as shown in the schematic diagram. You need to strip a USB cable. In this example, the ESP32-CAM and the motors are being powered using the same power source and it works well.

𝓝𝓸𝓽𝓮 the motors draw a lot of current, so if you feel your robot is not moving fast enough, you may need to use an external power supply for the motors. This means you need two different power sources. One to power the DC motors, and the other to power the ESP32. You can use a 4 AA battery pack to power the motors. When you get your robot chassis kit, you usually get a battery holder for 4 AA batteries.

Your robot should look similar to the following figure:
![image](https://user-images.githubusercontent.com/126898862/222800773-5cadf1ee-61bd-472a-a271-511104cc9f86.png)


𝐒𝐜𝐨𝐩𝐞

The system only detects pests and herbs and used pest spray to kill it rather than controlling field temperature and environment some pests are difficult to detect, proper attempt will be made to surely identify the pests and helps to remove them, it is important so that field health remain stable. Manual inspection cant be needed if this procedure is done in proper way. This will automatically reduce time consuming operations.The system uses an optical camera of low power to fully consume the area of the field.  Internet of Things in the agriculture sector has brought in a major evolution related to on-field pest management. A farm owner can now use different sensors to monitor the growth of pests and weeds and take further steps to manage them.

𝐂𝐨𝐝𝐞

You have to download the files in this Github directory 

𝐃𝐞𝐦𝐨𝐧𝐬𝐭𝐫𝐚𝐭𝐢𝐨𝐧

Open a browser on the ESP32-CAM IP address, and you should be able to control your robot. The web server works well on a laptop computer or smartphone.

![image](https://user-images.githubusercontent.com/126898862/222803565-00404cbc-4c02-463a-a277-6d82971b4da3.png)


𝐑𝐞𝐪𝐮𝐢𝐫𝐞𝐦𝐞𝐧𝐭𝐬

For this project, we’ll use the following parts:

『1』ESP32-CAM AI-Thinker with external antenna

『2』L298N Motor Driver

『3』Robot Car Chassis Kit

『4』Power bank or other 5V power supply

『5』Prototyping circuit board (optional)
