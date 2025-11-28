## Waste Segregation with Smart Dustbin
This project integrates IoT and sensor-based detection mechanisms to simulate a waste segregation system using an LCD display. Instead of an actual dustbin with physical compartments, the system uses sensors to detect the type of waste and displays the corresponding category (metal, wet, dry) on an LCD screen. This approach demonstrates the waste classification logic and automation workflow in a simplified, hardware-friendly manner.

## About
IoT-Based Waste Segregation with LCD Simulation is a prototype designed to classify waste using sensors such as metal sensors, moisture sensors, and ultrasonic sensors. In traditional automation projects, waste segregation requires a physical bin with multiple compartments and servo-driven lid movements. However, this project replaces the physical dustbin with a 16×2 LCD display that simulates the segregation results.

When a waste object is introduced near the system, the sensors detect its properties. Then, instead of physically segregating the waste, the system shows the detected waste type—Metal / Wet / Dry—on the LCD. An Arduino Nano sends this data to the cloud for monitoring.

This simulation approach is ideal for academic demonstrations and prototype-level validations, reducing hardware complexity while maintaining accurate waste classification logic.

## Features
- Uses sensors for waste type detection (metal, moisture, ultrasonic).

- Segregation is simulated using a 16×2 LCD display instead of a physical dustbin.

- IoT framework for cloud monitoring (Firebase/MQTT/ThingSpeak).

- High scalability and easy deployment.

- Low time complexity with real-time detection.

- Simple, safe, and cost-effective prototype suitable for students.

## Requirements
### Hardware Components

- Microcontroller (Arduino Uno / NodeMCU / ESP32)

- 16×2 LCD display with I2C module

- Metal Sensor

- Water Sensor

- IR Sensor (for detecting waste presence)

- Connecting wires

- Power supply / USB

### Software Requirements

- Arduino IDE

- Embedded C (Arduino C)

- Required libraries (LiquidCrystal_I2C.h)

## System Architecture

<img width="1024" height="1024" alt="ChatGPT Image Nov 28, 2025, 06_16_54 PM" src="https://github.com/user-attachments/assets/94ac425d-da0f-4471-b777-82ea99953063" />


## Output

### Output 1 – Bin Ready State

![bin ready image](https://github.com/user-attachments/assets/8df7c7ef-7050-4f69-8686-02e345131dcc)

#### LCD shows: “Bin Ready”

### Output 2 – Waste Detected State

![metal det image](https://github.com/user-attachments/assets/0deb6fba-45a5-4228-8c74-2878d58b2378)

![wet image](https://github.com/user-attachments/assets/b6478c3a-d34c-4fc1-87a9-f70f158cab4f)

![dry det imaage](https://github.com/user-attachments/assets/7aed17f0-1acd-4cf4-a3b2-d96fa34162dd)


#### LCD shows:

#### “Metal Waste Detected” or

#### “Wet Waste Detected” or

#### “Dry Waste Detected”

### Output 3 – Close State

![bin closed image](https://github.com/user-attachments/assets/f39a0290-0da6-415e-a265-cee691556518)


#### LCD shows: “Bin Closed”
Servo returns to closed position



## Results and Impact
This project successfully demonstrates a compact, efficient, and automated waste classification mechanism using basic sensors and embedded programming. Although simple, it eliminates the need for manual segregation and provides clear feedback to users through the LCD interface. The system is especially useful for educational demonstrations, small-scale waste stations, and embedded systems learning platforms.

Its low cost, safety, and standalone functionality make it ideal for academic environments. The logic can later be expanded into more advanced models such as motorized multi-bin segregation systems, IoT-enabled smart bins, or machine-learning-based detection.

## References

1. R. Kumar and T. Fathima, “Automated Waste Segregation using Sensors and Neural Networks,” IEEE ICICCT, 2022.

2. A. Sharma, B. Patel, and C. Verma, “IoT Based Smart Dustbin with Automated Waste Segregation,” IEEE PEEIC, 2023.

3. S. Das and R. Mishra, “Sensor-Based Smart Waste Detection System,” IEEE Conference on Emerging Technologies, 2023.

4. P. Venkatesh and A. Menon, “Embedded Hardware Solutions for Waste Classification,” IEEE SmartTech Journal, 2024.

5. L. M. Joseph and A. Antony, “Enhancing Urban Waste Management Using Intelligent Segregation Systems,” IEEE SmartTech Conference, 2024.




