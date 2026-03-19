# Marvel-task

# Task 2:API

# Objective

- Understand the concept of an **Application Programming Interface (API)** and how it enables communication between different software systems.
- Study the **working mechanism of APIs**, including request, response, and data exchange.
- Design and develop a **user interface (web or mobile app)** that makes API calls and displays the retrieved data effectively.

API stands for Application Programming Interface.It acts as a bridge between different software applications.
## How an API Works

**The Request:**  
The client sends a message to a URL (the Endpoint). This request has a **Method** like `GET` to get data or `POST` to send data. Usually, it also has an **API Key** for security.  

**Processing:**  
The server gets your request, checks who you are, and looks in its database to find the info you asked for.  

**The Response:**  
The server sends the data back, usually in **JSON**(Java script object notation) format. JSON is just text that is easy for computers to read.

![Weather App Screenshot](./weather_app.png)
# Task 4: Command line on ubuntu
# Objectives

- Create a folder named `test`.
- Change directory into that folder.
- Create a blank file without using any text editor.
- List the files in that folder.
- Create 2600 folders in this folder, where each folder is named like `M90` or `B56`.
  
  # Report
  
- Created a folder named `test`.
- Changed directory into the `test` folder.
- Created a blank file without using any text editor.
- Listed the files in the folder to verify the blank file.
- Created 2600 folders in the folder, each named like `M90` or `B56`.
- ![Ubuntu Screenshot](./Ubuntu1.jpeg)
![Ubuntu Screenshot](./Ubuntu2.jpeg)
![Ubuntu Screenshot](./ubuntu3.jpeg)

# Task 7:Create a portfolio webpage

I created a simple website using the knowledge I have of **HTML** and **CSS**.  
This project allowed me to practice structuring web pages with HTML and styling them with CSS.  

![Webpage](./)

# Task 8: Writing resource article using markdown
# Objective :
To write a resource article in markdown
# Report :
As part of the assignment, a technical article was written on the topic **"Robotic Dog"** using Markdown. The goal was to understand how Markdown can be used to structure and present technical content clearly without using complex tools or HTML.
# Outcome :
- Successfully created a well-structured technical article using Markdown  
- Gained a better understanding of both Markdown formatting and basic robotics concepts  
- Improved technical writing and documentation skills  
# Link to my article:
[Link Text](https://github.com/haripriyamuniraju07/Robotic-dog)

# Task 9:Tinkercad 

# Objective:
The objective of this task is to design and simulate circuits in Tinkercad that demonstrate the use of an ultrasonic sensor for distance measurement and object detection. 
# Report:
In this task, I learned about Tinkercad, which is an online platform used for 3D design, electronics simulation, and coding. It is beginner-friendly and helps in understanding basic concepts of design and circuits.
I successfully signed up on the Tinkercad platform by creating a new account.And built a simple radar system using an ultrasonic sensor that detects objects and displays distance

![Ultrasonic sensor](./Ultrasonic.jpeg)

# Task 10: Speed control of DC motor
# Objective:
The objective of this task is to explore and implement basic techniques for controlling DC motors using an Arduino UNO and the L298N H-Bridge motor driver. 
# Report :
Basic techniques to control DC motor using L298N motor driver
## 1. Direction Control (H-Bridge)

- Used to rotate motor **forward or backward**
- Achieved using an **H-Bridge circuit** (like L298N)
## **Concept:**
- IN1 HIGH, IN2 LOW → Forward  
- IN1 LOW, IN2 HIGH → Reverse  
- Both same → Stop  
## 2. Speed Control using PWM (Pulse Width Modulation)
- Controls motor speed by varying voltage effectively  
- Done using Arduino PWM pins  
## **Concept:**
- Higher duty cycle(The duty cycle is the percentage of time a signal stays ON (active/high) compared to the total time of one cycle) → Faster motor  
- Lower duty cycle → Slower motor  
![Dc motor](./DC_motor.jpeg)
## Components Used
- Arduino UNO
- L298N Motor Driver Module
- DC Motor
- RPS
 ## Working:
- The Arduino sends digital signals to the motor driver.
- The motor driver controls:
  Direction by switching polarity
  Speed using PWM (Pulse Width Modulation)
- The regulated power supply ensures a constant voltage, allowing smooth motor operation.
 
[Click to watch video](./DC_MOTOR.mp4)

