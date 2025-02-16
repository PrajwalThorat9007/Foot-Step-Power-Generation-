# Foot-Step-Power-Generation-
This project is designed to harness the mechanical energy from footsteps and convert it into electrical energy using piezoelectric discs. The generated power is stored in rechargeable 18650 lithium-ion batteries, which can be utilized for low-power applications. An Arduino Uno is used to process data and monitor power generation in real-time.
The system features an I2C-based LCD display that provides instant feedback by displaying either the generated voltage in millivolts (mV) or a simple "ON/OFF" status indicating whether power is being generated. Additionally, an LED indicator is integrated to visually signal when power is being produced. The Arduino reads analog voltage values from the piezoelectric setup and updates the display accordingly.
This project is an eco-friendly and sustainable energy solution, ideal for applications in public walkways, smart cities, and high-footfall areas. It demonstrates a practical approach to renewable energy generation while providing real-time monitoring and power storage capabilities.

Componenets Used in Project
1. Power Generation & Storage Components
- Piezoelectric Discs – 6 units (Connected in series for power generation)  
- 18650 Rechargeable Lithium-Ion Batteries (3.7V, 2600mAh each) – 2 units (Connected in series for power storage)  

2. Power Management & Circuit Components
1N4007 Diodes – 4 units (Used for rectification and protection)  
Electrolytic Capacitor (10µF, 25V) – 1 unit (For voltage stabilization)  
BC547 NPN Transistor – 1 unit (For controlling LED indication)  
Resistors:  
- 100kΩ Resistor – 1 unit  
- 10kΩ Resistor – 1 unit  
- 1kΩ Resistor – 1 unit  

3. Control & Monitoring Components
- Arduino Uno – 1 unit (Microcontroller for processing and monitoring)  
- I2C-Based LCD Display (16x2, 5V, Address 0x27) – 1 unit (For displaying power status or voltage readings)  
- Male-to-Male and Male-to-female Hookup Wires – Multiple units (For connections between components)  
- Breadboard – 1 unit (For prototyping and circuit assembly)  

4. Indication & Output Components 
- LED Strip (3V LEDs) – 1 unit (For power indication)
 
This list covers all essential components needed to build and operate the footstep power generation system.

Circuit Diagram
It is provided in repositry.

Step by step procedure
Diodes (1N4007):
-1st diode: Cathode (e6) to Anode (f6) .
-2nd diode: Anode (g6) to Cathode (g9).
-3rd diode: Anode (d6) to Cathode (d9).
-4th diode: Anode (f9) to Cathode (e9).

Capacitors and Resistors:
-10uF capacitor: Negative terminal to g14 and d14.
-100kΩ resistor: Connected between a14 and a19.
-10kΩ resistor: Connected between b19 and b23.
-1kΩ resistor: Connected between e24 and f24.


