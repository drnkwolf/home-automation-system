# Home Automation System

A home automation system build using Open Source hardware NodeMCU which is a wifi controlled micro-controller and Python's Flask framework.

## NOTE

This project was build as a part of my Minor 2 project for the academic session of 2021-21, semester fifth.

## Prerequisites

Python, NodeMCU, Arduino IDE, Wifi/Hotspot connection

## Technologies Used

* C++ - For micro-controller
* HTML/CSS/JS - For UI
* Flask - For Back-end services

## Despriction

* Use a simple Web interface with switches and buttons to control home appliance connected to relay board using a micro-controller.

* The frontend is build using vanilla HTML/CSS/JS and the server-side processing is done using Flask.

* The micro-controller communicates with the Flask application to get the status of different switches/button that were pressed to control applicances.

* A JSON file is used to store and synchronize the status of every micro-controller and the appliances connected to it.

## Installation

* Use the requirements.txt to install python dependencies.

* Flash the NodeMCU with the code in the nodemcu.ino file using Arduino IDE after changing the connection comments.

* Start the Flask application and connect the NodeMCU with the server.

## Project Partners

* [Nakul Garg](https://github.com/T0RPID0)
* [Sakshi Bansal](https://github.com/Sakshibansal172)
* [Shrey Arora](https://github.com/shreyyarora)