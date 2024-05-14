Smart Light

Description

The Smart Light is a centrally controlled IoT-enabled light bulb prototype designed for versatile use in various settings, including street lamps and indoor lighting. It offers two modes of operation: manual and automatic, allowing for dynamic adjustment of illumination. Both modes feature options for high or low-intensity lighting, aimed at reducing operating costs. The product also includes fault detection capabilities, enabling remote monitoring and minimizing downtime of failed lighting systems. With no need for batteries, the product operates efficiently on standard 230V AC mains supply.

Installation

Arduino IDE Setup:
1. Install Arduino IDE.
2. Add ESP8266 boards to the Arduino IDE.
3. Construct the circuit.
4. Upload the code from Arduino IDE.

Blynk Cloud and Dashboard Setup:
1. Create an account on Blynk.
2. Create a new project for your code.
3. Add necessary virtual variables and corresponding widgets for the interface.
4. Create a device under this project.
5. Copy the Blynk template ID and insert it into the Arduino code.

Usage

The Smart Light can be utilized for street lighting, public areas, or indoor lighting. Follow these steps for usage:

1. Connect the Smart Light to WiFi.
2. Provide the SSID and password of the WiFi hotspot in the code, for example:
   char ssid[] = "CHERRY";
   char pass[] = "Strawberry";
3. Connect your laptop to the internet.
4. Log in to your Blynk account.
5. Follow the installation steps provided above.
