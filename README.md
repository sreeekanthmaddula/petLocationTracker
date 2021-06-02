# petLocationTracker

Project PTS ( Pet Tracking system )

System Architecture of Pet Tracking system

Pet Diagram.png![image](https://user-images.githubusercontent.com/85250223/120531691-883ff580-c3fc-11eb-98a7-effab575155f.png)


Database: description of the tables and relations

![image](https://user-images.githubusercontent.com/85250223/120536213-7f055780-c401-11eb-9760-4a9dedd22b1d.png)

![image](https://user-images.githubusercontent.com/85250223/120536021-48c7d800-c401-11eb-80e1-1cd020584bf5.png)


![image](https://user-images.githubusercontent.com/85250223/120536042-50877c80-c401-11eb-8ac2-8082356fef16.png)


![image](https://user-images.githubusercontent.com/85250223/120536074-57ae8a80-c401-11eb-9ea4-229968732da3.png)



For a GPS-based tracking system, the system architecture as shown in Figure 1 is required:

1) A tracking device with a GPS receiver and antenna are needed.
2) Using GPS technology, the latitude and longitude data from satellites is received on the tracking device.
3) The data must then be transmitted through a wireless service to a server computer where the information is stored for later use.
4) The latitude and longitude is stored in the appropriate format specific to the API.
5) The user interface can now retrieve the needed data and using web services can render high quality mapping of the location of the desired receiver. 
 


Essential Components 

1. GPS Tracking Device 
     Receiver and antenna      Data-transmitting machine 
     Independent power supply 
     Mini processor  2. Wireless data transmission medium  3. Server computer  4. Web application  

How it works 

Stage 1 - Transmission of location information from satellites to tracking unit
Stage 2 - Transmission of collected data from tracking unit to server computer Stage 3 - Display location information in a graphical map display on the Web Application.

The tracking unit will allow the Owners to monitor the movement of their Pets over the Internet from any web-enabled device anytime of the day. 
 
Security

Physical Security
The concern here is surrounding physical security and the prevention of tampering and ingress onto the network via these appliances. 
1. Device ports security - the physical device could be tampered with and connected to if the encasement is not secured properly need to disable the USB udev at boot
2. Accessibility - Tamper proofing will be accomplished.


