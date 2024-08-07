# Ball-Tracking Robot
Have you ever wondered about how Tesla vehicles are able to track every single object they encounter? The ball-tracking robot can also carry out the same function with a smaller size.

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Vaibhav S | Ponderosa High School | Electrical Engineering | Incoming Junior |
![Ball Tracking Robot & Vaibhav](IMG_2186.png)
  
# Final Milestone
<iframe width="560" height="315" src="https://www.youtube.com/embed/Ya3F42WpKdc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

Since I finally got the raspberry pi camera working, I worked on improving the image processing to track the ball better. I also ran the motors to go forward and reverse but a few wires were in the wrong spot, causing the robot to spin instead of going forward or reverse. I swapped a few wires in different spots and the motors were finally able to move forward and backward. After debugging the motor wires, I pasted the motor code into the main image processing code. If the ball was farther away from the robot, the robot would move forward towards the ball. If the ball is very close, the robot would stop. 


# Second Milestone
<iframe width="560" height="315" src="https://www.youtube.com/embed/wealEdxyzZw " title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

Previously, I was having issues with the first raspberry pi camera module. Now in the second milestone, I was more careful with the new camera module and it was successfully connected to the raspberry pi. With the new raspberry pi module, I was able to take a picture. And then I ran the program for the raspberry pi camera to detect the ball and also connected the ultrasonic sensor code for them to work simultaneously to track the ball better. The plan later is to then make the motors follow the ball.

# First Milestone
<iframe width="560" height="315" src="https://www.youtube.com/embed/W6_buYm4MoE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

The ball tracking robot can locate certain objects using a camera and 3 sensors. The three ultrasonic sensors are used to detect objects from all directions. The motors allow the robot to move towards the ball. The H brick is what connects the motors to the breadboard. The breadboard carries out the instructions from the raspberry pi to the motors and sensors. 4 AA batteries are needed to power the motors. The raspberry pi is what gives the motors and sensors instructions. The biggest challenge this time was connecting the raspberry pi camera module. It was accidentally placed backwards and it broke.

# Schematics 


# Code
```c++
void setup() {
  // put your setup code here, to run once:
  Serial.begin(9600);
  Serial.println("Hello World!");
}

void loop() {
  // put your main code here, to run repeatedly:

}
```

# Bill of Materials

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Raspberry Pi | Running program | $104.99 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Robot Chassis | Body of the robot | $8.99 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Raspberry Pi Camera | Detecting the object | $6.99 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Screwdriver Kit | To build the chassis of robot | $6.99 | <a href="https://www.amazon.com/Small-Screwdriver-Set-Mini-Magnetic/dp/B08RYXKJW9/"> Link </a> 
| Ultrasonic Sensors | To detect distance between object | $9.99 | <a href="https://www.amazon.com/WWZMDiB-HC-SR04-Ultrasonic-Distance-Measuring/dp/B0CQCCGXCP/"> Link </a>
| H Bridges | To connect motors to raspberry pi | $8.99 | <a href="https://www.amazon.com/ACEIRMC-Stepper-Controller-2-5-12V-H-Bridge/dp/B0923VMKSZ/"> Link </a>
| Electronic Kit | Wires to connect sensors to raspberry pi | $9.99 | <a href="https://www.amazon.com/EL-CK-002-Electronic-Breadboard-Capacitor-Potentiometer/dp/B01ERP6WL4/"> Link </a> 
| Motors | To move the robot | $9.99 | <a href="https://www.amazon.com/AEDIKO-Motor-Gearbox-200RPM-Ratio/dp/B09N6NXP4H/"> Link </a>
| Multimeter | To test voltage to ensure proper connection | $12.99 | <a href="https://www.amazon.com/AstroAI-Digital-Multimeter-Voltage-Tester/dp/B01ISAMUA6/"> Link </a>
| Ball | Object for robot to track | $10.95 - $25.00 | <a href="https://www.amazon.com/CSI-Cannon-Sports-Duro-Skin/dp/B0000BY9GE/"> Link </a>
| Batteries | Power on the motors | $14.99 | <a href="https://www.amazon.com/Energizer-Batteries-Double-Alkaline-Battery/dp/B07TXNX6S2/"> Link </a>
| Power Bank | Keeps Raspberry Pi on while car is moving | $17.99 | <a href="https://www.amazon.com/SIXTHGU-Portable-Charger-Charging-Flashlight/dp/B0C7PHKKNK/"> Link </a> 
