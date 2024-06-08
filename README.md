#Final Project of IT course🌐
This project showcases a sample design for a mid-sized enterprise network, focusing on clarity and departmental segregation. The network utilizes a hierarchical structure with clearly defined layers:

Core: The core layer consists of a single ROOT CORE switch, which acts as the backbone of the network, providing high-speed connections between all other layers.
Distribution: The distribution layer comprises two switches, one for Management and Vice Managers (ROOT CORE port 10.40.0.0.0) and another for Workers (ROOT CORE port 10:30.0.0.0). These switches distribute traffic from the core layer to the access layer.
Access: The access layer consists of multiple switches, each dedicated to a specific department:
Sales (10.25.0.0.0)
Marketing (10.00.0.0.0)
Workers (VLAN 10, VLAN 20, VLAN 50)
Sale (VLAN 25)
Key Features:

Departmental Segregation: VLANs (Virtual LANs) are implemented to isolate traffic between departments, enhancing security and network performance.
Clear Labeling: Descriptive labels are assigned to ports and devices for improved network management and troubleshooting.
Redundancy: The use of two switches in the distribution layer provides redundancy in case of switch failure.
Methodologies:

Hierarchical Network Design: The network is structured in a hierarchical manner for better scalability, manageability, and security.
VLAN Implementation: VLANs are utilized to segment the network into logical broadcast domains, restricting traffic flow and improving security.

![image_of_project](https://github.com/Mosensei7/Desgining-a-network-for-a-company/assets/111107874/c79b91a5-3993-4b20-9c7b-6d61ab018c71)

