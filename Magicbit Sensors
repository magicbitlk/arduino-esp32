================
Magicbit Sensors
================

********************
01. Proximity Sensor
********************
1.1 Introduction
=================
In this example, you are learning how to use proximity sensor. This sensor (TCRT5000) uses reflection on a surface theory to working. From a white and polished surface reflects large percentage of light and from a black and rough surface absorbs (not reflect) large percentage of light that incidence on the surface.

Learning outcomes:
------------------
•	Reflection theory using with Infrared radiations.
•	Turning physical parameter to an analog electric signal.

1.2 Components
===============
•	Magicbit
•	Magicbit proximity sensor

1.3 Theory
===============

A proximity sensor is a sensor able to detect the presence of nearby objects without any physical contact. A proximity sensor often emits an electromagnetic field or a beam of electromagnetic radiation (infrared, for instance), and looks for changes in the field or return signal.

Features:
------------------ 
•	Supply voltage 3.3V ~ 5V
•	Detect distance 1mm ~ 8mm

1.4 Methodology
===============

As the first step, you should connect a Magicbit proximity sensor to Magicbit core board. For this you can use one side connector from four side connectors of the Magicbit core board or if you want to extend the length the connection you can use jumper wires.
For this example, the proximity sensor was connected to the upper left connector of the Magicbit core board.
Then connect the Magicbit to your pc and upload the code.
You can get outputs using serial monitor.

1.5 Coding
===============








Outputs: Serial monitor
 
Figure 1: Serial output when faced a black surface












1.6 Explanation

Const int: Defining input pin.
Serial.begin(9600): Setting baud rate.
analogRead: Read the data input of configured data pin.







***************
02. Tilt Sensor
***************

2.1 Introduction
===============
In this example, you are learning how to use Tilt sensor. Tilt sensor produces digital outputs such as high and low. Therefore, tilt sensor works as a switch that gives on and off states.

Learning outcomes
------------------
•	Digital reads and print them on serial monitor
•	Working principle of the tilt sensor

2.2 Components
===============
•	Magicbit 
•	Magicbit Tilt Sensor

2.3 Theory
===============

When the device gets power and is in its upright position, then the rolling ball settle at the bottom of the sensor to form an electrical connection between the two end terminals of the sensor.


 
Figure 3: Working priciple of tilt sensor [1]

2.4 Methodology

===============
As the first step, you should connect a Magicbit tilt sensor to Magicbit core board. For this, you can use one side connector from four side connectors of the Magicbit core board or if you want to extend the length the connection, you can use jumper wires.
For this example, the tilt sensor was connected to the upper left connector of the Magicbit core board.
Then connect the Magicbit to your pc and upload the code.
You can get outputs using serial monitor.





2.5 Coding
===============









Outputs: Serial monitor
 
Figure 4: High state of the tilt sensor
 
Figure 5: Low state of the tilt sensor



2.6 Explanation
===============

Const int TILTpin: Defining input pin
digitalRead: Read the data input of configured data pin.

***************
03. Flame Sensor
***************

3.1 Introduction
=================

A flame sensor module that consists of a flame sensor (IR receiver), resistor, capacitor, potentiometer, and comparator LM393 in an integrated circuit. It can detect infrared light with a wavelength ranging from 700nm to 1000nm.

Learning outcomes:
------------------
•	Using flame sensor for identify infrareds/heat bodies

3.2 Components
===============
•	Magicbit
•	Magicbit Flame Sensor

3.3 Theory
===============

IR receiver mainly use with a IR Transmitter, not only for identify heat bodies. IR light is emitted by the sun, light bulbs, and anything else that produces heat. That means there is a lot of IR light noise all around us. To prevent this noise from interfering with the IR signal, a signal modulation technique is used. In IR signal modulation, an encoder on the IR remote converts a binary signal into a modulated electrical signal. This electrical signal is sent to the transmitting LED. The transmitting LED converts the modulated electrical signal into a modulated IR light signal. The IR receiver then demodulates the IR light signal and converts it back to binary before passing on the information to a microcontroller.In here we use this sensor for identify flames.

3.4 Methodology
===============

As the first step, you should connect a Magicbit flame sensor to Magicbit core board. For this, you can use one side connector from four side connectors of the Magicbit core board or if you want to extend the length the connection, you can use jumper wires.
For this example, the flame sensor was connected to the upper left connector of the Magicbit core board.
Then connect the Magicbit to your pc and upload the code.
You can get outputs using serial monitor.

3.5 Coding
===============









3.6 Explanation
===============

Here we give an analogRead. That because we have to measure a range to take a decision that is there a flame or not.

















***************
04. DOOR Sensor
***************

4.1 Introduction
===============

A magnetic contact switch is a reed switch encased in a plastic shell so that you can easily apply them in a door, a window or a drawer to detect if the door is open or closed.
Learning outcomes:
------------------
•	Using magnetic door sensor.

4.2Components
===============


•	Magicbit
•	Magicbit Magnetic door sensor

4.3 Theory
===============

Almost all door and window sensors use a "reed switch" to determine when a protected area has been breached.  A reed switch consists of a set of electrical connectors placed slightly apart. When a magnetic field is placed parallel to the electrical connectors, it pulls them together, closing the circuit. Door sensors have one reed switch and one magnet, creating a closed circuit. If someone opens an armed door or window, the magnet is pulled away from the switch, which breaks the circuit and triggers an event.  [2]











4.4 Methodology
===============

First, take the Magicbit door sensor and connect it with the Magicbit core. In this example, we use 32th pin of Magicbit for implement this. After connect the door sensor upload following code for your Magicbit.
Then open your serial monitor in your Arduino IDE and see outputs while changing the door sensor module.
 
Figure 7: Door open state
 
Figure 8: Door closed state

4.5 Coding
===============









4.6 Explanation
===============

DOORpin: Defined input pin for door sensor



*******************
05. Magicbit Servo
*******************

5.1 Introduction
===============

A servomotor is an electrical device, which can push or rotate an object with great precision. If you want to rotate and object at some specific angles or distance, then you use servomotor. It is just made up of simple motor, which run through servomechanism.

Leaning outcome:
------------------
•	Using servo motor with Magicbit

5.2 Components
===============

•	Magicbit
•	Servomotor

5.3 Theory
===============

Servo motor works on the PWM (Pulse Width Modulation) principle, which means its angle of rotation, is controlled by the duration of pulse applied to its control PIN. Servomotor is made up of DC motor, which is controlled by a variable resistor (potentiometer), and some gears. Servomotors control position and speed very precisely. Now a potentiometer can sense the mechanical position of the shaft. Hence, it couples with the motor shaft through gears. The current position of the shaft is converted into electrical signal by potentiometer, and is compared with the command input signal. In modern servomotors, electronic encoders or sensors sense the position of the shaft.
A pulse of 1ms will move the shaft anticlockwise at -90 degree, a pulse of 1.5ms will move the shaft at the neutral position that is 0 degree and a pulse of 2ms will move shaft clockwise at +90 degree. [3]













5.4 Methodology
===============

For implement this project ESP32Servo library should be installed. Click here to download ESP32Servo library. Then install the library for Arduino IDE.
Follow these steps to install ESP32Servo library.
 
Figure 10: Iclude library -> Add.ZIP library
 
Figure 11: Select ZIP file


Then connect the magic servo motor t magic bit.
After completed those steps, upload following code for your Magicbit.

5.5 Coding
===============











5.6 Explanation
===============

Servo MagicServo: We should create an object in program for define the servomotor
MagicServo.attach: ‘attach’ means define which pin of the Magicbit connects to the servomotor.
For loop: In here, we use for loop to incrementing loop action. Because of this the servomotor increments its angle 0 to 180 and after complete this action reset to the start position. This action is continued repeatedly inside the ‘for loop’.

*******************
06. Motion Sensor
*******************

6.1 Introduction
=================

A motion sensor (or motion detector) is an electronic device that is designed to detect and measure movement. Motion sensors are used primarily in home and business security systems. PIR Sensor is short for passive infrared sensor, which applies for projects that need to detect human or particle movement in a certain range, and it can be referred as PIR (motion) sensor, or IR sensor. [4]
Learning outcomes:
------------------
•	Using motion sensor
•	Theoretical background of using Infrared waves in motion sensor

6.2 Components
==============
•	Magicbit
•	Magicbit Motion sensor

6.3 Theory
===============

When a human or animal body will get in the range of the sensor, it will detect a movement because the human or animal body emits heat energy in a form of infrared radiation. That is where the name of the sensor comes from, a Passive Infra-Red sensor. In addition, the term “passive” means that sensor is not using any energy for detecting purposes; it just works by detecting the energy given off by the other objects.











6.4 Methodology
===============

First, connect the motion sensor to your Magicbit and upload the following code to your Magicbit. In this demonstration like other demonstrations, we use D32 as the data pin.

6.5 Coding
===============








6.6 Explanation
===============

When some human being detected by the motion sensor, which is in the range of the sensor, the output of the serial monitor, will be displayed ‘1’. If not there will be displayed ‘0’.


***************
07. RGB Module
***************

7.1 Introduction
===============

An RGB LED has 4 pins, one for each color (Red, Green, Blue) and a common cathode. It has three different color-emitting diodes that can be combined to create all sorts of color.
R- Red
G- Green
B- Blue
Learning outcomes:
------------------
•	Using a RGB led and changing its color as the required

7.2 Components
===============
•	Magicbit
•	RGB module

7.3 Theory
===============

The RGB color model is an additive color model in which red, green, and blue light are added together in various ways to reproduce a broad array of colors. The name of the model comes from the initials of the three additive primary colors, red, green, and blue.
The main purpose of the RGB color model is for the sensing, representation, and display of images in electronic systems, such as televisions and computers, though it has also been used in conventional photography. Before the electronic age, the RGB color model already had a solid theory behind it, based in human perception of colors [5].

7.4 Methodology
===============

For this demonstration, you have to install Adafruit NeoPixel library. For more details Click here.
As usually connect the RGB module to your Magicbit, for this, we take data pin as pin 32.
After connect the RGB module to the Magicbit, connect it to your pc and upload following code.

7.5 Coding
===============














7.6 Explanation
===============

Adafruit NeoPixel library is for LED strips. However, it can be used for single RGB LED as your requirement (like this example).
‘LED.begin & LED.show’ are functions of Adafruit NeoPixel library for display the color on RGB led.
‘LED.setPixelColor’ is use to color led brightness values. (Eg:- 255 – maximum brightness & 0 – lowest brightness)

***************
08. Magnetic Sensor
***************

8.1 Introduction
 Magnetic sensors are able to detect magnetic fields and process this information. The outcome on the position, angle and strength (Hall Effect) or the direction (Magneto Resistive) of an applied magnetic field can be converted into specific output signals.

Learning outcomes:
------------------
•	Using Hall Effect sensor and detect magnetic fields.
•	Applications of Hall Effect Sensor


8.2 Components
===============
•	Magicbit
•	Soil Moisture Sensor


8.3 Theory
===============

There are actually, two different types of Hall sensors one is Digital Hall sensor and the other is Analog Hall sensor. The digital Hall sensor can only detect if a magnet is present or not (0 or 1) but an analog hall sensor’s output varies based on the magnetic field around the magnet that is it can detect how strong or how far the magnet is. In this project will aim only at the digital Hall sensors for they are the most commonly used ones. [6]

In a Hall Effect sensor, a thin strip of metal has a current applied along it. In the presence of a magnetic field, the electrons in the metal strip are deflected toward one edge, producing a voltage gradient across the short side of the strip (perpendicular to the feed current). 











8.4 Methodology
===============

Connect the magnetic sensor to the Magicbit. For this demonstration, we connect the magnetic sensor to D32 pin of the Magicbit.
After connect the magnetic sensor to the Magicbit connect it to your pc and upload the code below.






8.5 Coding
===============









8.6 Explanation
===============

This Magnetic sensor gives digital outputs. Therefor you can open the serial monitor and see the outputs.
‘1’ for occurred a magnetic field near to the sensor
‘0’ for there is no any considerable magnetic field near by the sensor

************************
9.0 Soil Moisture Sensor
************************

9.1 Introduction
===============
Soil moisture sensors typically refer to sensors that estimate volumetric water content. Another class of sensors measure another property of moisture in soils called water potential; these sensors are usually referred to as soil water potential sensors and include tensiometers and gypsum blocks.
Learning outcomes:
------------------
•	Using Soil moisture sensor and implement its applications
•	Working principal of soil moisture sensor

9.2 Components
===============
•	Magicbit
•	Soil Moisture Sensor

9.3 Theory
===============

Soil Moisture Sensor. Soil moisture is basically the content of water present in the soil. This can be measured using a soil moisture sensor which consists of two conducting probes that act as a probe. It can measure the moisture content in the soil based on the change in resistance between the two conducting plates.

9.4 Methodology
===============

Connect the soil moisture sensor to the Magicbit. As usually in here also we connect sensor module to the upper left (D32) connector on the Magicbit.
After connect the sensor module put it in to a wet soil mixture for get results.
Then connect the Magicbit to your pc and upload the code below.

9.5 Coding 
===============












9.6 Explanation
===============

‘output_value = map(output_value, 550,0, 0,100)’  - output_value is an user defined variable. For display a moisture percentage we should map the analog output value of the sensor given according to the sample (the wet soil mixture).
Fro serial monitor we can get our outputs.

***********************************
10. Temperature and Humidity Sensor
***********************************

10.1 Introduction
===============
A humidity sensor (or hygrometer) senses, measures and reports both moisture and air temperature. The ratio of moisture in the air to the highest amount of moisture at a particular air temperature is called relative humidity. Relative humidity becomes an important factor when looking for comfort.

Learning outcomes:
------------------
•	Using DHT11 sensor and getting outputs of temperature and humidity
•	Apply Temperature & Humidity sensor in projects

10.2 Components
===============
•	Magicbit
•	Temperature and Humidity Sensor

10.3 Theory
===============

The DHT11 detects water vapor by measuring the electrical resistance between two electrodes. The humidity-sensing component is a moisture holding substrate with electrodes applied to the surface. When water vapor is absorbed by the substrate, ions are released by the substrate, which increases the conductivity between the electrodes. The change in resistance between the two electrodes is proportional to the relative humidity. Higher relative humidity decreases the resistance between the electrodes, while lower relative humidity increases the resistance between the electrodes.
The DHT11 measures temperature with a surface mounted NTC temperature sensor (thermistor) built into the unit. [7]

10.4 Methodology
===============

First, you have to download and install library for DHT11. For more details and download the library 
Click here
Connect the Temperature & Humidity sensor to the Magicbit via left upper connector (D32). Then connect the Magicbit to your pc and upload the following code.

10.5 Coding
===============
