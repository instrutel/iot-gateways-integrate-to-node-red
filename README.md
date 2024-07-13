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
 * find---> 13 Jul 10:50:18 - [info] Server now running at http://127.0.0.1:1880/ this line and copy that link and paste in the browser you will see the flow structure which as shown in following image
   ![image](https://github.com/user-attachments/assets/2a48d707-086e-4f2e-a7f2-398ef10d474e)
 * for more information about node red flows follow the https://nodered.org/docs/
 * If it shows any node modules is require to install then install nodes follow the following steps
   1) Click on three lines shown on top right corner
   2) Click on Manage Pallate
   3) Click on Install
   4) Search module name in the search module barwhich you want 
      
### Hardware Configuration

### Authors 

### Screenshots
Energy Meter Dashboard <br />
![image](https://github.com/user-attachments/assets/2bd9b9d4-62c9-48f5-b6b8-81bab8b8bd23) <br />
Analog Input Dashboard <br />
![image](https://github.com/user-attachments/assets/8e6c49f9-c9e1-417f-b899-99cf6b4350e3) <br />
Digital Input Dashboard <br />
![image](https://github.com/user-attachments/assets/cb6b118b-3b6f-4d7c-9608-b713cd7df094) <br />
Digital Output Dahsoboard <br />
![image](https://github.com/user-attachments/assets/562cc4d9-ec7f-40ad-ac5c-a0158714d09f) <br />

