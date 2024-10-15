# Company Network Development

## Summary
This project involved the development and execution of a robust network infrastructure for a business with two sites (A & B), spanning four buildings and multiple departments. The project was executed using Cisco Packet Tracer, where routers, switches, and network security protocols were configured to establish efficient communication and data transfer across the network.

## Tools
- **Cisco Packet Tracer**
- **Networking Fundamentals**

**Note:** Cisco Packet Tracer must be installed to open the project.

For further information about the project, please refer to the project report.

## Project Documentation

This documentation outlines the progress made in developing a functional network for a company, emphasizing network security considerations. It details the project's development stages, lab work, and lessons learned over the course of the term.

### 1st Week
During the first week of the Security Ethics and Networking module, the focus was on understanding the significance of IP addresses in network communication. Key insights included:

- IP addresses uniquely identify devices on a network, facilitating communication.
- Each IP address serves as a numerical label that identifies and locates a device within the network.
- IP address classes categorize addresses based on the number of network and host bits, offering flexibility for various network sizes.
- The subnet mask's purpose is to distinguish between the network and host portions of an IP address, enabling efficient routing and communication.

### 2nd - 5th Week
From the second to the fifth week, the primary focus was on planning and designing the network topology. The tasks involved creating a custom topology, selecting appropriate network addresses, and determining the required number of hosts.

Key considerations included:
- The types of network transmission and the necessary devices for network functionality.
- Ensuring the project aligns with the OSI reference model.

The network design aimed to establish a company network across two distinct sites, incorporating multiple buildings and departments. The initial design included:
- Two routers for inter-site communication.
- A switch for each building.
- Five computers and one printer for each department.
- A server in the IT department.

![Initial Topology](https://github.com/user-attachments/assets/ab0fa53b-8695-49a8-b5e3-ad88ccc53361)

### 6th - 7th Week
With the network topology defined and devices connected, the configuration phase commenced. The configurations were as follows:

**Site A:**
- **Building 1 (Switch 1):**
  - Management: `192.168.10.1/24`
  - Financial: `192.168.20.1/24`
  - Human Resources: `192.168.30.1/24`
- **Building 2 (Switch 2):**
  - IT: `192.168.40.1/24`
- **Building 3 (Switch 3):**
  - Customer Support: `192.168.50.1/24`

**Site B:**
- **Building 4 (Switch 4):**
  - Marketing: `192.168.60.1/24`
  - Sales: `192.168.70.1/24`
  - Advertising: `192.168.80.1/24`

**Router Configurations:**
- **Router 1:**
  - Serial 0/3/0: `128.0.0.1`
- **Router 2:**
  - Serial 0/3/0: `10.0.0.2`

### 8th Week
After configuring the VLANs, sub-VLANs were necessary for routing and communication between VLANs. During testing, routing issues between the two sites and VLANs arose and were subsequently resolved.

**Router Configuration Adjustments:**
- **Router 1:**
  - Serial 0/3/0: `128.0.0.1`
- **Router 2:**
  - Serial 0/3/0: `128.0.0.2`

An additional router was added to enhance connectivity among the buildings. Below is a screenshot of the final topology:

![Final Topology](https://github.com/user-attachments/assets/a6fef4ee-3867-41e1-8b60-1fdcef62a8b8)

### Reflection & Conclusion
This project enabled the application of theoretical networking concepts to a practical scenario, enhancing my understanding of networking principles. The final topology reflects a successful network design implementation, providing a solid foundation for future network management endeavors. However, the network security aspects did not fully meet the required standards in terms of firewall configurations, indicating an area for improvement in future projects.

**Note:** The final version of the project is attched above this readme file.
