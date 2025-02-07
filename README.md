# Smart-Dustbin

An automated **Smart Dustbin** that opens its lid when detecting an object within a specified distance using an **ultrasonic sensor** and **servo motor**. This project enhances hygiene by enabling contactless waste disposal.

## Components Required  
- **Arduino Uno**  
- **Ultrasonic Sensor (HC-SR04)**  
- **SG90 Micro Servo Motor**  
- **9V Battery**  
- **Dustbin**  
- **Jumper Wires & Double-Sided Tape**  

## Software Required  
- [**Arduino IDE**](https://www.arduino.cc/en/software)  


## Working Principle  
- The **ultrasonic sensor** detects an object within **50 cm**.  
- The **servo motor** opens the dustbin lid for **3 seconds**.  
- The lid **automatically closes** after the set duration.  

## Setup & Installation  
### **Step 1: Connect the Components**  
- Assemble the **circuit** as per the connections.  
- Mount the **servo motor** on the dustbin.  

### **Step 2: Upload the Code**  
- Open **Arduino IDE**.
-  Copy & paste `arduino_code.txt` into the editor.  
- Select the **correct board & COM port** in *Tools* menu.  
- Click **Upload** to flash the code to Arduino.  

### **Step 3: Power & Test**  
- Connect a **9V battery** to the Arduino.  
- The smart dustbin is **ready for use**!  

