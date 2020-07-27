## Home Automation

The role of smart devices that are connected to one another and that can share data between each other is becoming increasingly important in everyday life. Commonly referred to as the Internet of Things (IoT), a practical application of such technology is to monitor and automate various facets of a home. The purpose of this project is to develop a reactive, concurrent, message-driven system that receives real-time data from smart devices in a home. At the same time, the system is designed to be flexible and customizable in allowing a homeowner to configure their desired settings, such as heating, lighting, humidity, and locking.

## System Features

The functionality offered by the smart home automation system is listed below:

1. Temperature Control
2. Humidity Control
3. Lighting Control
4. Door and Window Locking
5. Motion Sensor Monitoring
6. Smoke Detection Monitoring
7. Carbon Monoxide Monitoring
8. Electricity Usage Monitoring
9. Water Consumption Monitoring
10. Electrical Appliance Control
11. Audio and Video Control
12. Lawn Sprinkler Control
13. Robot Vacuum Control
14. Internet Status Monitoring
15. Security Camera Monitoring

The system is designed to be modular so that additional functionality may be added later on. Users may also choose to disable certain functionality if desired and enable only those smart devices that they would like.

## Technology Stack

There exist several libraries that allow for actor-style programming in languages that do not have such functionality built in. Some of the more recent developments include CAF for C++, Pykka for Python, Actix for Rust, and Akka for Java and Scala. The core of the home automation system is developed using the Akka framework via the Scala programming language. The system also consists of a consumer facing web interface built using React. A MySQL database resides underneath the entire system.

## Development Environment

It is recommended, but not necessary, to use IntelliJ IDEA when developing the code. Follow the instructions on the Getting Started page via the Scala Documentation:

1. Getting Started With Scala in IntelliJ ([Link](https://docs.scala-lang.org/getting-started/intellij-track/getting-started-with-scala-in-intellij.html))
2. Building a Scala Project with IntelliJ and SBT ([Link](https://docs.scala-lang.org/getting-started/intellij-track/building-a-scala-project-with-intellij-and-sbt.html))
3. Testing Scala in IntelliJ with ScalaTest ([Link](https://docs.scala-lang.org/getting-started/intellij-track/testing-scala-in-intellij-with-scalatest.html))

Note that this repository contains only the source code associated the home automation system itself and **not** the IntelliJ project configuration files. Please create a new project using the steps outlined above, and then add the source code in this repository to the newly created project. The second step above provides instructions on how to define a run configuration and how to then execute the code.
