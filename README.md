<h1>Smart Ticketing Machine for City Bus Management</h1>

This project aims to develop a multi-purpose ticketing device for TSRTC buses. The proposed device will use IoT components to track real-time occupancy of buses, provide online ticketing, manage student bus passes, and provide real-time bus location.

<h2>Features</h2>

<h3>1. Real-time occupancy tracking:</h3> 
The device will use infrared sensors to count the number of passengers entering and exiting the bus. This data will be transmitted to the TSRTC server in real time, allowing TSRTC to track bus occupancy and make informed decisions about scheduling and routing.
Online ticketing: The device will have a built-in QR code scanner. Passengers can scan QR codes on their smartphones to purchase tickets. This will eliminate the need for passengers to carry cash or wait in line to purchase tickets.
Student bus pass management: The device will have a built-in RFID reader. Students can scan their RFID cards to board the bus. This will streamline the boarding process and reduce the risk of fare evasion.
Real-time bus location: The device will use the NEO-6M GPS module to track its location. This data will be transmitted to the TSRTC server in real time, allowing passengers to track the location of their bus and plan their journey accordingly.
Hardware:

ESP32 microcontroller
SIM800L GPRS module
NEO-6M GPS module
RC522 RFID reader writer module
LCD display screen
Infrared sensors
Power supply
Enclosure
Software:

The device will be programmed using the Arduino IDE. The firmware will be responsible for the following tasks:

Reading data from the infrared sensors, GPS module, and RFID reader
Calculating the bus occupancy and fare
Transmitting data to the TSRTC server
Displaying information on the LCD display screen
Deployment:

The devices will be installed on all TSRTC buses. They will be powered by the bus's electrical system. The devices will communicate with the TSRTC server using the GPRS module.

Benefits:

The proposed system will provide a number of benefits, including:

Improved efficiency: The system will streamline the ticketing process and reduce the risk of fare evasion, making it more efficient for both passengers and TSRTC.
Increased convenience: Passengers will be able to purchase tickets online and track the location of their bus in real time, making their journey more convenient.
Better decision-making: TSRTC will be able to track bus occupancy and make informed decisions about scheduling and routing.
Conclusion:

The proposed IoT-based bus ticketing system has the potential to improve the efficiency, convenience, and reliability of bus transportation in Hyderabad.
