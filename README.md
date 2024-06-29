# Arduino Uno IR Receiver Module

#### Project Overview

This project demonstrates how to use an IR receiver module with an Arduino Uno to receive and decode infrared signals from a remote control or another IR transmitter. The Arduino reads the IR signals using the IRremote library and displays the received IR codes on the serial monitor in hexadecimal format.

#### Components Needed

- **Arduino Uno**
- **IR Receiver Module**
- **Jumper Wires**
- **Breadboard**

#### Block diagram


#### Circuit Setup

1. **Connect the IR Receiver Module to Arduino Uno:**
   - **Signal pin of the IR Receiver Module:** Connect to digital pin 11 on the Arduino Uno.
   - **Vcc pin of the IR Receiver Module:** Connect to 5V on the Arduino Uno.
   - **GND pin of the IR Receiver Module:** Connect to GND on the Arduino Uno.

#### Instructions

1. **Circuit Setup:**
   - Connect the IR receiver module to the Arduino Uno as described in the circuit setup section.

2. **Code Upload:**
   - Open the Arduino IDE and create a new sketch.
   - Copy and paste the provided Arduino code into the sketch.

3. **Testing:**
   - Upload the code to the Arduino Uno.
   - Open the serial monitor with a baud rate of 9600.
   - Point an IR remote control towards the IR receiver module and press buttons. Observe the serial monitor to see the received IR codes in hexadecimal format.

#### Applications

- **Remote Control Systems:** Use in projects where remote control functionality is required.
- **Home Automation:** Implement in smart home systems for controlling devices using IR remotes.
- **Consumer Electronics:** Integrate into electronics projects for receiving IR commands.

#### Notes

- Ensure the IR receiver module is correctly connected to the Arduino Uno and powered.
- Use the IRremote library for easy handling of IR signals and decoding.
- Different remote controls may use different IR codes; adjust your application logic based on the specific IR codes received.

---

🌐 [ProjectsLearner](https://projectslearner.com/learn/arduino-uno-ir-receiver-module)  
📧 [projectslearner@gmail.com](mailto:projectslearner@gmail.com)  
📸 [Instagram](https://www.instagram.com/projectslearner/)  
📘 [Facebook](https://www.facebook.com/projectslearner)  
▶️ [YouTube](https://www.youtube.com/@ProjectsLearner)  
📘 [LinkedIn](https://www.linkedin.com/in/projectslearner)

Crafted with ❤️ by ProjectsLearner