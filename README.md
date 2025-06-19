**TASK 01:-SIMON SAYS** 

Simon Says is a fun memory game where you have  to press buttons in the same order as the LEDs light up. In each round, a new LED is added to the sequence, and the pattern becomes harder to remember. I created this game using a simulation link with ESP32, pushbuttons, and LEDs. The ESP32 is programmed to randomly flash LEDs, and each LED is linked to a specific push button.In every round, the ESP32 checks if the player presses the correct buttons. If the sequence is correct, another light is added and the game continues. 
If the player presses the wrong button, ‘Game Over’ is shown on the serial monitor. 

https://www.youtube.com/shorts/bhjwMAMpnOg 

https://github.com/Usha-005/simon-says--esp32 

**TASK 02:-BASICS OF MQTT PROTOCOL AND OTHER COMMUNICATION PROTOCOLS** 

MQTT (Message Queuing Telemetry Transport) is a lightweight messaging protocol ideal for IoT applications, especially where networks are slow or unreliable. It works on a publish-subscribe model where devices send messages to a broker(A server that receives all messages), and the broker delivers them to subscribed devices. MQTT supports many features like QoS levels, retained messages, and last will messages, which help ensure reliable communication.example like bluetooth,wifi,I2C etc… 

 

Communication and Key Network Protocols: 

* HTTP: Transfers web pages and data. 

* WebSocket: Enables real-time communication. 

* SMTP: Used for sending emails. 

* TCP/IP: The base protocol for internet communication. 

* IP: Handles addressing and routing 

* DNS: Converts website names into IP 

 

**TASK 3: BASICS OF CREATING A WEBSITE** 

I made a website in JSFiddle which changes colour when we click on that. And I learnt how to create front end and back end, I used HTML ,CSS, JAVA Script to build it. And also to build back end used server side language like python. As result of this, I created a simple wed server that toggles the colour of the background when a button is clicked. 

* HTML(Hyper Text Markup Language) → Structure of a webpage (headings, buttons, images, text, etc. 

* CSS (Cascading Style Sheets) → Styles the webpage (colors, fonts, animations, layout) 

* JavaScript (JS) → Makes the webpage interactive (click events, forms, animations, real-time updates) 

 

 

**TASK 4: MQTT PUBLISH AND SUBSCRIBE USING CLOUD MQTT** 

An MQTT broker is used to enable communication between a Python script (publisher) and an ESP32 (subscriber). The ESP32 connects to Wi-Fi, then connects to the MQTT broker using the internet, and it publishes data like sensor readings.The Python script sends commands like "LED 1 ON" or "LED 2 OFF" to specific topics. 
This setup allows precise, remote control of each LED independently, making it efficient for IoT automation projects. 

  

 

**TASK 6: SENDING DATA TO THINGSPEAK**

This task involves using a DHT11 sensor, ESP32, and ThingSpeak to monitor temperature data and we have to create the account in think speak to get API key. The DHT11 sensor measures temperature and humidity, using a thermistor and humidity sensor, sending the data to the ESP32 for processing .After it gives temperature at every 05 seconds. And this temperature can be visualized as over time, by plotting retrived data with Matplotlib.  

* ESP32- write API key (to send data to Thinkspeak (e.g.,temp,humidity)) 

* Python code-read API key (to read data from Thingspeak and plot using matplotlib.) 

 

 

 

**TASK 7: COMMUNICATION USING I2C PROTOCOL** 

I2C (Inter-Integrated Circuit) is a communication method that uses just two wires — SDA (data) and SCL (clock) — to send data between devices. It's mostly used for short-distance communication between a microcontroller and other parts like sensors, displays, or motor drivers.I2C works on a master-slave system, where one device acts as the master and controls one or more slaves. Each slave has a unique address, so the master knows which one it’s talking to. In my circuit, I used ESP32 as the master and Arduino UNO as the slave. 
Messages from both devices were shown on their own serial monitors, which helped me see the communication clearly. 

 

 

**TASK 8: FLASHING MORSE CODE** 

In this task, I used the ESP32 to create a simple web server. It shows a basic HTML page where the user can type a message. The setup includes the ESP32, an LED, and a few wires. Once the message is typed and sent, the ESP32 reads the text, turns it into Morse code, and then blinks the LED with short and long flashes to show the dots and dashes for each letter and number. 

 

 

 

 

**TASK 9: SOIL MOISTURE SENSOR** 

In this task, I used a Capacitive Soil Moisture Sensor along with the ESP32 to measure the moisture level in soil.The sensor has a capacitive probe that creates an electric field. When it's placed in soil, the capacitance changes depending on how much water is in the soil because water has a higher dielectric constant than dry soil or air. As the moisture increases, the capacitance also increases. This change is turned into an analog signal, which the ESP32 reads. 
Usually, higher values mean dry soil, and lower values mean moist soil. 

 

 

 

**TASK 10: READ AND DISPLAY VITALS** 

This task uses the MAX30100 sensor, ESP32, and an app made with MIT App Inventor. The MAX30100 measures heart rate and oxygen levels using red and infrared LEDs. The ESP32 collects this data and acts as a web server. The app gets the data from the ESP32 through HTTP and shows it on the screen. It also gives alerts if the heart rate or oxygen level goes out of the normal range. 

**TASK 11: FIRE ALARM SYSTEM WITH EMAIL ALERTS** 

For this task, I used an infrared flame sensor, ESP32, and an LED. The flame sensor detects infrared radiation from fire using a photodiode. When a flame is present, it sends a digital signal to the ESP32. The ESP32 monitors this signal, and if fire is detected, it turns on the LED. The LED was not blinked because the sensor didn’t detect any flame or strong infrared source during testing. 

 

 

 

 

 

 

 
 
