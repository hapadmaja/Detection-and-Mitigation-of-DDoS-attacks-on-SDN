In this project we have attempted to detect and Mitigate DDos Attcks on Software Defined Networks.
We have used Virtual Box and Ubuntu Operating system for operating environment. We have mininet and ryu controller to set up a mini network topology and then send legitimate traffic and benign Traffic .
This will detected by the controller programs wriiten in python.
The Flow statistics is collected by the start_traffic_collection.py program. This program will store it in FlowStatsFile.csv in comma-seperated format.
Depending on the traffic flow, the devices form which the data is recieved. The flow is percieved as legitimated normal flow or attack flow.
The Mitigation modules are then invoked to inorder to mitigate the attack.
