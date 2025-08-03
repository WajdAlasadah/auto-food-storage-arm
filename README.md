🤖 Automated Food Warehouse Robot
This project presents a smart robotic system designed to fully automate the storage and handling of food items in a warehouse without any human intervention. The solution involves a 6-DOF robotic arm, sensors, a conveyor belt, and smart shelving.

📌 Project Description
The system automates the food storage process by:

Receiving items through a conveyor

Using a vision camera to recognize the type of food

Measuring the weight using sensors

Moving the item to the appropriate location via a robotic arm

Automatically updating the storage database

The goal is to improve speed, accuracy, and safety in warehouse operations.

🦾 Robot Design
Component	Function
Robotic Arm	Picks up and places food items
Rotating Base	Rotates the arm 360° to access all storage areas
Multiple Joints	Allow precise movement and flexibility
Vision Camera	Identifies the type of food item
Weight Sensor	Detects the weight of each item
Conveyor Belt	Brings items to the robot from the entry point
Smart Shelving	Stores items in categorized sections automatically
Control Unit	Coordinates sensors, motors, and storage logic

📐 Working Envelope
Parameter	Value
X-axis Range	200 cm
Y-axis Range	150 cm
Z-axis Range	100 cm
Rotation	360°
Maximum Load	5 kg
Degrees of Freedom	6 DOF

🧠 Execution Algorithm
Start the system

Check warehouse readiness (power, sensors, etc.)

Receive food items through the conveyor belt

Use the vision camera to identify item type

Measure the item’s weight using a weight sensor

Determine the best storage location

Move the robotic arm to pick and place the item

Update the storage database with item info and location

Return the system to standby

Repeat for each new item or shut down when finished
