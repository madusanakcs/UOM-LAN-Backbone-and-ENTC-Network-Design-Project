# UOM LAN Backbone and ENTC Network Design Project
 
This is a group project that involves the design and simulation of the backbone network for the University of Moratuwa (UOM) and the internal network of the Engineering Technology (ENTC) building. The project aims to create a scalable and efficient network infrastructure for UOM.

## Table of Contents

- [Project Description](#project-description)
- [Design Approach](#design-approach)
- [Network Diagram](#network-diagram)
- [IP Addressing Scheme](#ip-addressing-scheme)
- [Component Justifications](#component-justifications)
- [Router and Switch Specifications](#router-and-switch-specifications)
- [Bill of Quantities](#bill-of-quantities)
- [Simulation Results](#simulation-results)
- [Packet Tracer Files](#packet-tracer-files)
- [Routing Configuration](#routing-configuration)

## Project Description

The project involves designing the backbone network for UOM, connecting various academic faculties, administrative offices, the library, and the data center building (CITeS). Additionally, we are simulating the LAN network for the ENTC building as a reference design.

## Design Approach

Our design approach considers long-term use (20-25 years) while optimizing total cabling costs. We follow best practices and justify design choices.

## Network Diagrams

![Network Diagram - ENTC bulding ](https://github.com/madusanakcs/UOM-LAN-Backbone-and-ENTC-Network-Design-Project/blob/main/stage%202/Screenshot%202023-09-20%20012734.png)
![Network Diagram - Univercity of Moratuwa](https://github.com/madusanakcs/UOM-LAN-Backbone-and-ENTC-Network-Design-Project/blob/main/stage%202/Screenshot%202023-09-20%20012814.png)

-The network diagram depicts all connected buildings, their nodes, and bandwidth allocation for each link.

## IP Addressing Scheme

- IPv4 and IPv6 addressing schemes have been designed to efficiently allocate IP addresses to each building and network node.

## Component Justifications

- We selected single-mode vs. multimode fiber for specific segments based on factors like distance and future scalability.
- Routers and switches have been chosen based on their capacity and compatibility with the network requirements.

## Router and Switch Specifications

- Router/switch specifications are as follows:
  - Router Model: Cisco XYZ
  - Switch Model: Cisco ABC
  - ...

## Bill of Quantities

- We prepared separate Bill of Quantities (BOQ) for passive and active components, taking reference from the ENTC network.

## Simulation Results

We conducted simulations to demonstrate the network's functionality and resilience. Results include:

- Routing paths for accessing LMS servers.
- Routing paths after a backbone link failure.
- Routing paths for collaborative research project sessions.

## Packet Tracer Files

- The Packet Tracer simulation files are available in the 'packet-tracer-simulations' directory.

## Routing Configuration

- We implemented OSPF for routing within the backbone network. Redundancy ensures continuous access to key resources.

---

**Note:** All students were involved in designing the routing plan, OSPF configuration, and simulations. We have provided the necessary configuration files and can explain and run simulations upon request.



