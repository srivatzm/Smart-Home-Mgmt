# Smart-Home-Mgmt
Contains the Requirement received for the subjected topic.
Smart Home Management 

Requirement 

There are smart home devices/appliances (like TV, Refrigerator, AC, Microwave etc) which can be interfaced with NETCONF/YANG protocol (or RESTCONF). 
Require a smart home management solution which can manage all these smart devices via NETCONF/YANG. 
Each of the device has some common characteristics and some specific characteristics. 
The system which would manage these devices should
1.	Configure the devices 
2.	Collect data periodically 
3.	Troubleshoot and control the devices
4.	Visualize the device details and provide some metrics

Come up with a specification document/wiki/presentation which should provide the design of the solution, high level data model (YANG), use cases and user stories definition which can be the input to the implementation.
High level Data Model:
1.	Data model common to all the devices
a.	Example: 
i.	IP/Port
ii.	Power consumed
iii.	Voltage
iv.	Current
v.	Uptime 
vi.	etc

2.	Data model specific to device type
a.	Example:
i.	For Refrigerator:
1.	Fridge temperature
2.	Freezer temperature
ii.	For AC:
1.	Temperature
2.	Mode
3.	Off Timer 
iii.	and so on  
