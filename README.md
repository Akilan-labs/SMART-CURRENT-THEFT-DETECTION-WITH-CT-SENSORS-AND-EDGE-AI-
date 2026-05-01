⚡ Smart Electricity Theft Detection using Edge AI (STM32)

📌 Overview
Electricity theft is not just a financial concern—it directly impacts grid stability, operational efficiency, and fair energy distribution. This project presents a smart, embedded solution that detects unauthorized electricity usage in real time using current sensing and Edge AI.

Built on an STM32 microcontroller, the system leverages CT (Current Transformer) sensors and the ACS712 current sensor to monitor power flow. By applying lightweight AI models at the edge, it identifies abnormal patterns that may indicate electricity theft—without relying on cloud processing.

🎯 Key Highlights
⚡ Real-time current monitoring and analysis
🧠 Edge AI-based anomaly detection (TinyML approach)
🔍 Detection of illegal tapping and abnormal load patterns
🔌 Fully embedded solution (no continuous internet required)
💡 Cost-effective and scalable for smart grid applications

🛠️ Hardware Used
STM32 Microcontroller (any compatible variant)
CT Sensor (Current Transformer)
ACS712 Current Sensor Module
Power supply unit
Breadboard / PCB setup

💻 Software & Technologies
Embedded C (STM32CubeIDE)
Edge AI / TinyML model
Signal processing & filtering techniques
Serial communication for monitoring output
⚙️ System Working

The system continuously measures current from the power line using CT and ACS712 sensors. These readings are fed into the STM32, where a lightweight AI model analyzes the data in real time.

Under normal conditions, current follows predictable patterns. When unauthorized tapping or abnormal load behavior occurs, the system detects deviations and flags them as potential theft.

This on-device intelligence ensures:
Faster response
Lower latency
Independence from cloud infrastructure

🧩 System Architecture
Power Line 
   ↓
CT Sensor / ACS712 
   ↓
STM32 Microcontroller 
   ↓
Edge AI Model 
   ↓
Anomaly Detection Output

🚀 Getting Started
1. Clone the Repository
2. Open in STM32CubeIDE
Import the project into STM32CubeIDE.

4. Hardware Setup
Connect:
CT sensor to current measurement line
ACS712 to analog input
Ensure proper grounding and power supply

5. Flash the Code
Upload the firmware to your STM32 board.

6. Monitor Output
Use serial monitor to view real-time readings and alerts.

📈 Future Scope
This project can be extended to:
🌐 IoT-based remote monitoring (cloud dashboards)
📍 Location-based theft identification
📱 Mobile app notifications
🤖 More advanced AI models for higher accuracy

🌍 Applications
Smart Grid Infrastructure
Power Distribution Companies
Industrial Energy Monitoring
Rural Electrification Systems

🤝 Why This Project Matters
        Electricity theft leads to significant economic losses and affects honest consumers. This project demonstrates how embedded systems + AI can provide a practical, scalable solution to a real-world problem—bridging the gap between innovation and impact.

👨‍💻 Author

Akilan M
Final Year – Electronics and Communication Engineering
Kongu Engineering College
