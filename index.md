# Ball-Tracking Robot
Have you ever wondered about how Tesla vehicles are able to track every single object they encounter? The ball-tracking robot can also carry out the same function with a smaller size.

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Vaibhav S | Ponderosa High School | Electrical Engineering | Incoming Junior

**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**

![Headstone Image](logo.svg)
  
# Final Milestone
<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE



# Second Milestone
<iframe width="560" height="315" src="https://www.youtube.com/embed/wealEdxyzZw " title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

Previously, I was having issues with the first raspberry pi camera module. Now in the second milestone, I was more careful with the new camera module and it was successfully connected to the raspberry pi. With the new raspberry pi module, I was able to take a picture. And then I ran the program for the raspberry pi camera to detect the ball and also connected the ultrasonic sensor code for them to work simultaneously to track the ball better. The plan later is to then make the motors follow the ball.

# First Milestone
<iframe width="560" height="315" src="https://www.youtube.com/embed/W6_buYm4MoE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

The ball tracking robot can locate certain objects using a camera and 3 sensors. The three ultrasonic sensors are used to detect objects from all directions. The motors allow the robot to move towards the ball. The H brick is what connects the motors to the breadboard. The breadboard carries out the instructions from the raspberry pi to the motors and sensors. 4 AA batteries are needed to power the motors. The raspberry pi is what gives the motors and sensors instructions. The biggest challenge this time was connecting the raspberry pi camera module. It was accidentally placed backwards and it broke.

# Schematics 
Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. 

# Code
Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs. 

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
Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. 

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Raspberry Pi | Running program | $104.99 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Robot Chassis | Body of the robot | $8.99 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Raspberry Pi Camera | Detecting the object| $6.99 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
