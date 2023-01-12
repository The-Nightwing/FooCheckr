# Food Condition Monitoring - A Project for Prototyping interactive systems (DES130)

This project utilizes sensor data to monitor the condition of food in a container and alert the user when the food is spoiled. It does this by sending SMS to the user’s mobile phone whenever the food gets spoiled, and now it's now to safe to keep your food in the container.

This project is the major project of the course Prototyping interactive systems (DES130). The goal of the project is to demonstrate the ability to prototype an interactive system that solves a real-world problem.

## Hardware 
- Arduino microcontroller
- DHT11 Temperature and Humidity Sensor
- Alcohol sensor (MQ-3)
- Light-Dependent Resistor (LDR)

## Software
- Arduino IDE
- Mit App Inventor

## Setting up the Hardware

1. Connect the DHT11 Temperature and Humidity sensor to the Arduino. The DHT11 has three pins: VCC, Data, and GND. Connect the VCC pin to 3.3V, the Data pin to digital pin 8, and the GND pin to GND.

2. Connect the Alcohol sensor (MQ-3) to the Arduino. The MQ-3 has three pins: VCC, Data, and GND. Connect the VCC pin to 5V, the Data pin to A0, and the GND pin to GND.

3. Connect the Light-Dependent Resistor (LDR) to the Arduino. The LDR has two pins: one connects to A1 and the other connects to GND.

## Setting up the Software

1. Download and install the Arduino IDE.

2. Download the code provided above and open it in the Arduino IDE.

3. Connect your Arduino to your computer via USB cable.

4. In the Arduino IDE, select the     appropriate board and port.

5. Upload the code to the Arduino.

6. Download and install Mit App Inventor.

7. Create a new project in Mit App Inventor and import the app code. A screenshot of the blocks design is included in the repository for reference.

8. Configure the app to receive data from the Arduino via Bluetooth or other communication protocol.

9. Set threshold values for each sensor data, if any of the sensor data goes beyond that threshold value, it will consider the food as spoiled.

10. Test the app and ensure that it is properly receiving data from the Arduino and sending SMS when food is spoiled.

11. Connect the arduino to power source and place it inside the container.

## Usage

1. Place the container with food and arduino inside.

2. Turn on the power to the arduino.

3. Wait for the arduino to gather sensor data and send it to the app.

4. Check the app for the status of the food and take appropriate action if necessary.

This code is provided as-is. It is your responsibility to ensure that it is safe and compliant with all applicable laws and regulations.

### Note
The repository also includes the .apk file for the app, so that it can be directly installed on an Android device.
