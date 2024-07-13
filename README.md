# Utility Monitoring System 

### With the help of Iot Gateway this project provides a remote monitoring system for multiple devices like  
---> 1) Analog Input  <br/>
---> 2) Analog Output  <br/>
---> 3) Digital Input  <br />
---> 4) Digital Output

#### Table Of Content 
* Description
* Installation
* Usage
* Contributing
* License
  <br />
### Description 
* Use Iot Gateway for efficient communication between connected device through RS485 or Ethernet connection and monitoring them with the help of unique topic name.
* Use of Node-RED's visual flow editor for easy configuration and customization  <br />
* Operate all the devices with the help of an easy to use interface of node red dashboard <br/><br/>
![image](https://github.com/user-attachments/assets/6d78505d-cb15-46a3-bb73-145a6d86cb82)

### Installation Guide
1. **Node.js:** Ensure you have a compatible version of Node.js installed: https://nodejs.org/en
2. **Node-RED:** Follow the installation guide for your operating system: https://nodered.org/docs/getting-started/local.            
   npm install -g --unsafe-perm node-red
3. **MYSQL Database:** Storing and Retrieving data coming from the devices we need a database so ensure you have a database installed in your computer system here we use MYSql database for download it follow the link https://dev.mysql.com/downloads/installer/
4. **Clone the repository:**
   * 1 clone The repo
   
         https://github.com/instrutel/iot-gateways-integrate-to-node-red
   * 2 Go to the iot-gateways-integrate-to-node-red folder
    
           cd iot-gateways-integrate-to-node-red

    * 3 Install the node red dependencies
  
          npm install
    * 4 Run
  
          node-red
![image](https://github.com/user-attachments/assets/8963f29f-c56d-41e2-9008-5c756b5b7c4b)
 * find---> 13 Jul 10:50:18 - [info] Server now running at http://127.0.0.1:1880/ this line and copy that link and paste in the browser

### Usage 
Node-red :
Node-RED uses graphical flows and nodes, which have individual components in a flow to essentially create a program. 
Its a open-source tool


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
