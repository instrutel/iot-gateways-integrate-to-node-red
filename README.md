# Utility Monitoring System 

### This project provides a remote monitoring system for multiple devices like 
### 1) Analog Input  2) Analog Output 3) Digital Input  4) Digital Output With the help of Iot Gateway 
### Table Of Content 
* Introduction
* Features
* Installation
* Usage
* Contributing
* License
  <br />
### Description 
* Monitor analog and digital devices data and control them remotely.
* Use Iot Gateway device for efficient communication between devices and the monitoring system with the help of unique topic name.
* Use of Node-RED's visual flow editor for easy configuration and customization  <br /><br />
![image](https://github.com/user-attachments/assets/6d78505d-cb15-46a3-bb73-145a6d86cb82)

### Installation Guide
1. **Node.js:** Ensure you have a compatible version of Node.js installed: https://nodejs.org/en
2. **Node-RED:** Follow the installation guide for your operating system: https://nodered.org/docs/getting-started/local.            
   npm install -g --unsafe-perm node-red
3. **Required Nodes:** (If applicable, list specific Node-RED nodes needed)
   - Install using the Node-RED package manager or manually.
4. **MYSQL Database:** Ensure you have mysql database installed in your computer system
5. **clone this repository**
git clone https://github.com/instrutel/iot-gateways-integrate-to-node-red/tree/main
# Go into the repository
cd electron-node-red
# Install the yarn install tool globally
sudo npm i -g yarn
# Install project dependencies
yarn
### Usage 
Node-red :
Node-RED uses graphical flows and nodes, which have individual components in a flow to essentially create a program. 
Its a open-source tool
![image](https://github.com/user-attachments/assets/a647746e-fdd2-47c8-a962-334dc6ede887)


for accessing a data from multiple devices using iot gateway 
Iot Gateway is connected to the multiple devices using Ethernet or RS485 connection.
Iot Gateway collects data from the devices and send that data to the iot hub through a topic name.
We can access this data by subscribing that unique topic name. 
through node js we can operate that devices using node red dashboard 
Node red : Low-code programming interface for event driven application
### Hardware Configuration

### Authors 

### Screenshot
Energy Meter Dashboard
![image](https://github.com/user-attachments/assets/2bd9b9d4-62c9-48f5-b6b8-81bab8b8bd23)
Analog Input Dashboard
![image](https://github.com/user-attachments/assets/8e6c49f9-c9e1-417f-b899-99cf6b4350e3)
Digital Input Dashboard
![image](https://github.com/user-attachments/assets/cb6b118b-3b6f-4d7c-9608-b713cd7df094)
