# Environmental Mapping System
![Project Setup](main/project_setup.png)
An innovative project utilizing ultrasonic sensors, Arduino, and servo motors to create a real-time environmental mapping system. The system detects objects, calculates distances, and visually represents the data on an LCD screen.

## Features
- **Real-Time Object Detection**: Uses ultrasonic sensors to identify objects and measure distances.
- **360-Degree Scanning**: Employs a servo motor for full-angle coverage.
- **Data Visualization**: Displays distance and angle information on an LCD screen.
- **Algorithmic Processing**: Converts distance and angle data into vector representations for spatial mapping.

## Components Used
- **Arduino Uno**: Microcontroller for managing the system.
- **Ultrasonic Sensor (HC-SR04)**: Detects objects and calculates distances.
- **Servo Motor (SG90)**: Rotates the sensor for wide-area scanning.
- **LCD Screen (PCD8544)**: Displays real-time data.
- **Solderless Breadboard**: Simplifies circuit assembly.
- **Jumper Wires**: Connects components securely.

## How It Works
1. **Object Detection**: The ultrasonic sensor emits a signal and measures the time taken for the echo to return, calculating the object's distance.
2. **Angular Scanning**: The servo motor rotates the sensor to scan the environment at 1-degree intervals up to 180 degrees.
3. **Data Processing**: Distances and angles are converted into vector data.
4. **Visualization**: The LCD screen displays the detected object's distance and angle for real-time tracking.

## Installation and Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/OmerNachmani/Environmental-Mapping-System-with-Ultrasonic-Sensors.git
