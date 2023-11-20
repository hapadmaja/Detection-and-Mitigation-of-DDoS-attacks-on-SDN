In this project we have attempted to detect DDos Attcks on Software Defined Networks.
We have used Virtual Box and Ubuntu Operating system for operating environment. We have used mininet and ryu controller to set up a mini network topology . We have developed Python code to generate legitimate traffic and benign Traffic on the mininet side.
This will detected by the controller programs wriiten in python on the ryu controller side.
The Flow statistics is collected by the start_traffic_collection.py program. This program will store it in FlowStatsFile.csv in comma-seperated format.
Depending on the traffic flow, the devices form which the data is recieved. The flow is percieved as legitimated normal flow or attack flow.
Once DDoS traffic is detected, an alert prompt is displayed on the screen.
