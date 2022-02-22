# INTRODUCTION
This aims at monitoring of physical parameters using Microcontroller via GSM interface using different sensors.
The sensors can be used to sense the temperature, light, humidity, water-level etc and those can be sensed at a far distance using
SMS technology without any electronic circuitry for data transfer. The temperature observing framework utilizing GSM experiences
three phases flag molding circuit, analog to digital converter and sending messages to portable devices. The project consists of two
modules-one is the temperature observing and the other is the temperature control.
For this reason, we utilized the LM35 sensor which characterizes the parameters of the temperature sensor. The Simple yield of
LM35 is opened up through a procedure of signal molding. Opened up signal is bolstered into an ADC for advanced information.
This computerized information is exchanged to an LCD for showing the result. ATMega328 microcontroller is utilized for this
strategy. A Modem is likewise associated with this controller for the remote correspondence of the information through GSM
innovation by getting an alarm through SMS..
# BLOCK DIAGRAM
![bd](https://user-images.githubusercontent.com/75032547/154969937-de722807-dae9-4b98-aabe-88d9833a233f.jpg)
# HIGH LEVEL IMPLEMENTATION

| ID  | High level requirements |
| ------------- | ------------- |
| HL1  |Detecting the Temperature|
| HL2  | Storing the data  |
| HL3  | sends a message to given number  |


# LOW LEVEL IMPLEMTATION
| ID  | Low level requirements |
| ------------- | ------------- |
| H1L1  |Temperaure detection using LM35 sensor|
| H2L1  | Storing the data into cloud  |
| H3L1  | Sends message using GSM modem |
# SENSOR AND ACCUTATORS
ATmega328 Microcontroller - It is an eight (8) bit Microcontroller. It can handle the data sized of up to eight (8) bits. It operates ranging from 3.3V to 5V.

LM35 Temperature Sensor - It can detect temperature and the operating temperature range is from -55°C to 150°C.

Relay - It is an electrically operated switch. Many relays use an electromagnet to mechanically operate a switch.

GSM Modem - A GSM modem is a wireless modem that works with a GSM wireless network which sends and receives data through radio waves.
Like GSM mobile phone, a GSM modem requires a SIM card from a wireless carrier for its functioning.

LCD display - LCD is a liquid crystal display. An LCD is a flat-panel display that make use of light-modulating properties of liquid crystals.

# APPLICATION
- It is used in industries and factories.

- Efficient temperature controlling.
