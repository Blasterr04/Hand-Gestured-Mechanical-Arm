This project, "Hand Gesture Controlled Mechanical Arm," is a robotic arm that mimics the movements of a human hand based on hand gestures. The project utilizes advanced technologies such as the ESP32 microcontroller, flex sensors, and servo motors to achieve precise control over the robotic arm's movements. Our primary goal was to demonstrate a hands-free control mechanism for robotic manipulation, with potential applications in manufacturing, healthcare, and assistive technology.

 Introduction:
The "Hand Gesture Controlled Mechanical Arm" project aims to create a robotic arm capable of mimicking human hand movements based on hand gestures. This report outlines the components used and the construction process of the robotic arm. The project utilizes ESP32 microcontroller, flex sensors, and servo motors for precise control of the robotic arm's movements. This project aims to demonstrate a hands-free control mechanism for robotic manipulation, useful in various fields such as manufacturing, healthcare, and assistive technology.

 Components Used:
•	5 Flex Sensors: Detects finger bending and generates analog signals
•	5 Servo Motors: Actuates the fingers of the robotic hand
•	Arduino UNO Board: Maps flex sensor data and sends it to ESP32
•	Microcontroller (ESP32): Interprets Arduino data and controls servo motors
•	Connection Pins: Connects flex sensors, servo motors, and microcontrollers to a breadboard
•	Springs: Bends the robotic hand according to flex sensors
•	3D Printer: 3D prints the model of the hand made on SolidWorks
•	Mechanical Framework: Provides structure for the robotic hand
•	Power Supply: Provides electrical power to servo motors

 Construction
1) Printed Robotic Arm
- Designed using SolidWorks and printed using a 3D printer
- Each finger printed in two parts and connected using springs
- Nylon strings used to connect finger parts to servo motors for movement control

2) Glove with Flex Sensors
- Designed with flex sensors attached to each finger
- Flex sensors connected to a breadboard, then to an Arduino UNO board for data collection
- Data transmitted via wires to one ESP board, then wirelessly to another ESP board controlling the servo motors

Working Principle
1. User wears the glove and moves fingers
2. Flex sensors detect movement and send analog data to Arduino UNO board
3. Arduino UNO processes data and transmits it via wired connection to ESP board
4. ESP board wirelessly transmits data to another ESP board connected to servo motors
5. Servo motors rotate, pulling nylon strings connected to robotic fingers, mimicking user finger movements

 Testing and Calibration
- Calibrated flex sensors for accurate finger movement measurement
- Tested the robotic hand with various hand gestures to verify accuracy and responsiveness
- Fine-tuned the control algorithm to optimize performance

 Applications
- Manufacturing Automation: Assembly, pick-and-place operations, and quality inspection
- Rehabilitation and Healthcare: Assists individuals with physical disabilities in daily tasks and rehabilitation exercises
- Education and Research: Educational tool for learning robotics, embedded systems, and sensor interfacing; research in human-machine interaction and gesture recognition
 Problems Faced
- Manufacturing and Design Issues: Adjusted finger parts to stabilize the model, fixed dimensional and design errors
- Data Transmission Issues: Switched from Arduino Uno and nrf24l01 to ESP32 for reliable wireless data transmission
- Inefficient Output: Managed flex sensor sensitivity changes, frequently adjusted value mapping to maintain output accuracy

 
Conclusion
We successfully moved each finger at about 130 degrees using servo motors based on data from flex sensors. The project demonstrated a functioning hand-gestured robotic arm, with programming logic, Wi-Fi connectivity, and 3D model design completed by our team. This project highlights the integration of flex sensors, Arduino boards, ESP boards, servo motors, and 3D printing technology to create a mechanical robotic arm controlled by hand gestures, showcasing potential applications in industries requiring precise and intuitive control mechanisms.

