# Distance Measurement using Ultrasonic Sensor and Arduino
https://harshshinde.hashnode.dev/distance-measurement-using-ultrasonic-sensor-and-arduino

# Arduino:

Arduino is an open-source electronics platform that encompasses both hardware and software components. At its core, Arduino boards feature microcontrollers, such as the popular Atmel AVR family, with built-in input/output pins for interacting with external components. The Arduino Integrated Development Environment (IDE) provides a user-friendly interface to write, compile, and upload code to the board, simplifying programming with its C/C++ language support. The platform is renowned for its versatility, making it accessible for beginners and advanced users alike. Its vast library support enables easy integration of sensors, displays, and communication modules. With a strong community and ample documentation, Arduino has become a go-to choice for prototyping, hobby projects, and education in the world of electronics and embedded systems.

# Ultrasonic Sensor:

An ultrasonic sensor is a device that uses sound waves at frequencies higher than the human audible range to measure distances and detect objects without physical contact. It works based on the principle of sending ultrasonic pulses and measuring the time it takes for the sound waves to bounce back after hitting an obstacle. This time measurement helps calculate the distance between the sensor and the object. Ultrasonic sensors are widely used in applications such as distance measurement, object detection, liquid level sensing, and collision avoidance in various industries, including robotics, automotive, and industrial automation.

# Working of Ultrasonic Sensor:

An ultrasonic sensor works by emitting high-frequency sound waves (ultrasonic pulses) and measuring the time it takes for the waves to bounce back after hitting an object. The sensor then calculates the distance to the object based on the time of flight of the sound waves. This distance measurement technique allows the sensor to detect objects or measure distances without any physical contact, making it useful in various applications such as distance sensing, object detection, and collision avoidance.

The speed of sound in air is nearly 344 m/s

Formula: Distance = Speed * Time

In the code, the “duration” variable stores the time taken by the sound wave traveling from the emitter to the receiver. That is double the time to reach the object, whereas the sensor returns the total time including sender to object and object to receiver. Then, the time taken to reach the object is half of the time taken to reach the receiver. so we can write the expression as,

Distance = Speed of Sound in Air * (Time Taken / 2)

Note: Speed of sound in air = 344 m/s.

# Components Used:

Arduino Uno

Ultrasonic sensor

16x2 LCD

Bread board

Potentiometer 10K

Connecting wires

# Pins:

VCC: +5VDC

Trig: Trigger (INPUT)

Echo: Echo (OUTPUT)

GND: GND


# Setup:

Connect the Echo pin of the sensor to the pin of the Arduino.

Connect the Trigger pin of the sensor to the pin of the Arduino.

Navigate to Tools and select board and port.

Verify and compile the code, then upload the code to the Arduino Uno board.

Monitor the output in the Serial monitor or in LCD Display.

# Conclusion

Indeed! The Ultrasonic sensor is a versatile and widely used sensor in DIY electronics projects. It offers non-contact distance measurement, object detection, and position sensing capabilities, making it ideal for various applications. With the help of an Arduino board, it becomes easy to interface and utilize the sensor's data for a wide range of projects, including robotics, home automation, and more. Its affordability and ease of use make it a popular choice among hobbyists and students for creating innovative and interactive projects.
