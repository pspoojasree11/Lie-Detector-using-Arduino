
🔍**Lie Detector using Arduino**

Our skin is amazing! It provides a medium for us to experience the sense of touch, it keeps infections out and keeps innards in but I bet you didn't know that our skin changes conductivity depending on many different things one being our mood! It called Electrodermal activity (EDA) and there's a really interesting Wikipedia page you can read here. The basics are that our skin changes its conductivity depending on how we feel.

📋 **Overview**
The Lie Detector using Arduino is a prototype that focuses on detecting deceptive responses based on electrodermal activity (EDA). The system uses a skin conductance sensor to measure changes in skin resistance, which can indicate stress or nervousness often associated with lying. The data is analyzed by an Arduino microcontroller to detect variations in the subject's response and determine whether they are being truthful or deceptive.


🚀 **Features**
Electrodermal Activity (EDA): Measures changes in skin resistance to detect physiological signs of stress.
Arduino Controlled: Uses an Arduino microcontroller to process sensor data and analyze responses.
Real-time Detection: Provides immediate feedback on the subject’s truthfulness based on sensor readings.
User-friendly Interface: Simple setup with minimal components for easy experimentation and testing.


🛠️ **Components Used**

Arduino: Microcontroller used for data processing and control.
Skin Conductance Sensor: Measures electrodermal activity to detect stress levels.
Buzzer: Provides auditory feedback when a lie is detected.
Wires & Jumper Cables: For connecting the components.
LCD Screen (optional): Displays real-time sensor data and results.


🧠 **Working Principle**

The system works by measuring the skin conductance levels (SCL), which can change based on the subject's emotional state. When a person lies, their body often experiences a stress response, causing a temporary increase in skin conductance. This change is detected by the sensor, and the Arduino processes the data to determine the likelihood of deception.


📦 **Installation**

Assemble the Hardware:
Connect the skin conductance sensor to the Arduino.
Optionally, attach an LCD screen to display the data.
Wire the buzzer to the microcontroller for feedback.

Upload the Code:
Upload the provided code to the Arduino using the Arduino IDE.

Conduct the Test:
Ask the subject questions while monitoring the sensor readings.
The system will analyze the skin conductance data to detect stress responses associated with lying.
