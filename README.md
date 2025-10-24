Electroglide Hoverboard: is a one-wheel self-balancing hoverboard powered by a 24V hub motor, controlled using an ESP32 microcontroller.  
The system integrates MPU6050 gyroscope and accelerometer for balancing, an L298N motor driver for motor control, and NEO-6M GPS for location tracking.  
Bluetooth/Wi-Fi enable mobile connectivity and remote control.

--- Features:
- Self-balancing using MPU6050 sensor
- GPS-based live tracking via NEO-6M
- Motor control using L298N driver
- Remote monitor through Wi-Fi (Blynk IoT)
- mechanical frame body
- Removable Li-ion battery pack for portability

---Hardware Used:
- ESP32 / ESP32-CAM  
- MPU6050 (Gyroscope + Accelerometer)  
- L298N Motor Driver  
- NEO-6M GPS Module  
- 24V Hub Motor
- LM2595 BUCK Convertor(IOT power)
- lithium-ion battery pack(hoverboard power)

---Software & Libraries:
- Arduino IDE  
- WiFi.h  
- Wire.h  
- MPU6050.h  
- TinyGPS++  
- Blynk IoT  

---Working Principle:
The hoverboard maintains balance using MPU6050 readings for pitch and roll angles.  
Motor speed and direction are adjusted in real-time via ESP32 PWM signals to the L298N.  
GPS provides location tracking and navigation feedback to the mobile app.

---Circuit Diagram:
[Mechinical body](https://github.com/user-attachments/assets/9b3460b4-5ae2-4597-af44-b878d27dee56)
[Interior fitting](https://github.com/user-attachments/assets/26aa4169-8339-4089-a8bc-9d7855dc0fed)
[Hoverboard images](https://github.com/user-attachments/assets/81d17f99-011c-49a2-9311-0cb704cc97e9)
[Battery pack assemble](https://github.com/user-attachments/assets/0bddd4f1-2660-4b49-b55c-0d38157dcdd9)
[Battery pack](https://github.com/user-attachments/assets/ce47a8e9-fc0f-4e0b-aabc-1dd413fb2a6e)
[Circuit Diagram](https://github.com/user-attachments/assets/b0913856-4c41-4ba6-9721-8be07c5eb28e)
[Block Diagram](https://github.com/user-attachments/assets/ae012505-c02c-4e67-addc-da8383ae4256)
[Flow Chat](https://github.com/user-attachments/assets/8666a407-4292-411e-b1db-0b45b4cb7fc7)
[Mobile View](https://github.com/user-attachments/assets/a1e27c4c-af17-4810-93ff-01450e837278)
[Working video](https://github.com/user-attachments/assets/6a837c68-fbfe-48ff-a7e1-b5b24899746a)


---Future Enhancements:
- Object detection using ESP32-CAM  
- Auto return-to-home navigation  
- Battery management using fuel gauge IC  

---Author:
Karthik Uttla
E-mail: karthikuttla@gmail.com
instagram:https://www.instagram.com/karthik_143_uk_?igsh=dG43NTN6aGhwOTBh
Linkedin:http://www.linkedin.com/in/karthik-u-88933528a
