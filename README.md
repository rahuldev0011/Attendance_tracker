🏠 IoT Smart Home Automation
📘 Project Overview
This project demonstrates a simple IoT-based Smart Home Automation System that allows users to control household appliances (like lights or fans) remotely using Wi-Fi.
The system uses the NodeMCU (ESP8266) microcontroller to host a web server, enabling users to switch devices ON or OFF via a web interface accessible from any smartphone or laptop connected to the same network.

⚙️ Key Features
🔌 Control multiple home appliances wirelessly using Wi-Fi.
🌐 Built-in web server hosted on NodeMCU (no external app required).
⚡ Low-cost and power-efficient system design.
🧠 Demonstrates real-world IoT implementation and automation concepts.
🧰 Components Used
NodeMCU (ESP8266)
2-Channel Relay Module
LED Bulbs / Fans (as loads)
Jumper Wires
Breadboard
Power Supply (5V)
💻 Software & Tools
Arduino IDE
C / Embedded C Programming
Web Server using HTML
Local Wi-Fi Network
🔍 Working Principle
NodeMCU connects to the local Wi-Fi network.
A small web page is hosted on the NodeMCU, displaying buttons for ON/OFF control.
When the user clicks a button on the webpage, NodeMCU receives an HTTP request.
NodeMCU activates or deactivates the connected relay, turning the appliance ON or OFF.
🧩 Applications
Home and Office automation
Energy-saving systems
Remote control for disabled or elderly users
Prototype for smart city applications
🚀 Future Enhancements
Add Google Assistant / Alexa voice control
Integrate with cloud database (Firebase / Blynk) for remote access
Include temperature or motion sensors for automatic operation
👨‍💻 Author
Rahul Dev
Final Year B.Tech (Electronics & Communication Engineering)
