![image](https://github.com/user-attachments/assets/8a58328f-b1c8-4f28-8fea-6a87ec98cbc0)# Smart-Cooling-System-IoT-Final-Project
![image](https://github.com/user-attachments/assets/870cd53d-c439-4892-b208-cfad536ca1fe)

The project involves building Smart Air System working based on  sensor monitoring and control system using an ESP32 microcontroller. The system reads data from various sensors (temperature, humidity, IR, flame, gas, and smoke) and Fan and Air pump take appropriate actions based on the sensor readings. as well as we create Flutter mobile Application to Controls the Fan and Air pump.

Fan 2 Control (Gas, Smoke, or Fire Detection)
Turns On: When any of the following conditions are met:
The gas sensor (MQ5) detects gas above a certain threshold.
The smoke sensor (MQ2) detects smoke above a certain threshold.
The flame sensor detects fire.
Turns Off: When all the following conditions are met:
The gas sensor detects gas below the threshold.
The smoke sensor detects smoke below the threshold.
The flame sensor does not detect fire.

## MAQTT
Wi-Fi and MQTT Integration: The Two ESP32 also connects to a Wi-Fi network and communicates with an MQTT broker. It publishes sensor readings and control actions to specific MQTT topics and receives control commands via MQTT.


## Node Red
We Connect The MQTT Serve With NODE RED by passing into MQTTin flow :-
1-Cluster URL 
2- Username
3- Password
4-Topic Name 
![image](https://github.com/user-attachments/assets/4f742314-8840-4dc9-b95b-7a6870e6c36c)

After that we display the Signals that are coming From Sensors into Line Charts , Graphs and Gauges .
![image](https://github.com/user-attachments/assets/ebe24ca7-50f0-40d3-98fa-670b257c70db)

##Mobile Application!

Sign in /sign up Screens :-
We connect The App with Firebase to Store the database of users 
![image](https://github.com/user-attachments/assets/03eaac55-1287-4148-b925-a0efdc789e63)

![image](https://github.com/user-attachments/assets/44859763-7248-4bf1-a1eb-1b726b39ec57)

Sensors Dashboard That Contains Graphs For each Sensor to Show us the Signals That Coming from Our Sensors:-
![image](https://github.com/user-attachments/assets/e04d5f17-4571-4397-a9b3-4d04dc0111c4)

We Can Control our Fan and Air pump through MQTT Server where we Submit The Statue of Actuators that we would prefer, and we can easily subscribe on The topic of Fan and Air Pump :-


![image](https://github.com/user-attachments/assets/e24db329-1fda-4b10-9294-a2795877178d)








