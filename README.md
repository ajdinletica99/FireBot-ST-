FireBot – Remote Firefighting Robot
Problem We Are Solving

In July 2024, a large wildfire affected approximately 50 hectares of forest near Bugojno, threatening an archaeological site and requiring intervention from the Armed Forces of Bosnia and Herzegovina.

The incident highlighted a serious problem:

Firefighters cannot safely access mined or inaccessible terrain
Traditional firefighting methods are slow and limited
Human intervention in such environments is highly dangerous

More information: RTV Slon – Wildfire near Bugojno

Our Solution: FireBot

FireBot is a remotely controlled firefighting robot designed to enable fire suppression without requiring humans to enter dangerous zones.

It provides real-time control and visual feedback while performing firefighting tasks in hazardous environments.

Key Features
Control Range: up to 30 meters
Mobility System:
Two main drive motors (forward movement)
Auxiliary rear wheels for stability on uneven terrain
Control System:
Laptop → RemoteXY application → Bluetooth module → Arduino
Visual System:
Front camera (movable in two directions)
Rear fixed camera for situational awareness
Firefighting System:
Water sprayer system controlled via relay module (Arduino)
Fire extinguisher activated using a servo/actuator
Technologies Used
Arduino Mega (main controller)
Raspberry Pi (visual system support)
Bluetooth module (wireless communication)
RemoteXY mobile application
H-Bridge motor drivers
Relay modules (pump, lights, actuator control)
Actuators (fire extinguisher activation)
C / C++ (Arduino programming)
Battery-powered system for mobility and autonomy
Dual-camera setup (front + rear)
Functionalities
Remote control from a safe distance
Fire suppression using water or fire extinguisher
Real-time video feedback from cameras
Dual-direction water sprayer rotation (left/right)
Stable movement on uneven terrain
Safe operation in hazardous environments
Project Goal

To develop a low-cost robotic system capable of assisting firefighting operations in dangerous, inaccessible, and high-risk areas, reducing risk to human lives.

Developed By

Students of Secondary Technical School Bugojno
Project focused on robotics, embedded systems, and real-world problem solving.
