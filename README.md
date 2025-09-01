# Ultrasonic-Range-Finder-
Ultrasonic Range Finder

A portable and low-cost distance measurement system built using an HC-SR04 ultrasonic sensor and Arduino Uno. The device displays real-time distance readings on a 16x2 LCD and includes a buzzer alert when an object is too close. This project can be used for obstacle detection, robotics applications, or as a learning project for embedded systems.

🚀 Features

Measures distance in centimeters using the HC-SR04 ultrasonic sensor.

Displays real-time readings on a 16x2 LCD.

Buzzer alert when distance < 20 cm (threshold adjustable in code).

Portable, low-cost, and suitable for robotics and automation applications.

🛠️ Tech Stack

Microcontroller: Arduino Uno

Programming Language: Embedded C (Arduino IDE)

Components:

HC-SR04 Ultrasonic Sensor

16x2 LCD Display

Buzzer

Breadboard & Power Supply

⚡ Circuit Diagram (Connections)
Component	Arduino Pin
HC-SR04 Trig	9
HC-SR04 Echo	10
LCD RS	7
LCD E	6
LCD D4	5
LCD D5	4
LCD D6	3
LCD D7	2
Buzzer	11
📜 Code

The complete Arduino code is available in this repository:
Ultrasonic Range Finder Code

🔧 How It Works

The HC-SR04 sensor sends ultrasonic waves and measures the echo time.

The Arduino calculates distance using:

Distance (cm)
=
Time (µs)
×
0.034
2
Distance (cm)=
2
Time (µs)×0.034
	​


The LCD displays live distance readings.

The buzzer turns on if the distance is below 20 cm (configurable).

📷 Demo

(Add images or GIFs of your setup and LCD display here)

🚦 Future Improvements

Add serial logging for debugging.

Add OLED display for compact design.

Integrate with ESP32/IoT for wireless monitoring.

📌 Author

👩‍💻 Yuktha Dodda Rangappa
🔗 https://github.com/YukthaDoddaRangappa
