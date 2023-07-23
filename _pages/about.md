---
permalink: /
title: "Overview " 
excerpt: "Overview"
author_profile: true
redirect_from:
- /about/
- /about.html
---

Hi, my chinease name is Saijie Lu. My current work experience mainly involves two aspects of data center networking:the control plane and the data forwarding plane. 
Regarding the control plane, I have been primarily involved in developing SDN controller functionality based on ODL technology.
As for the data forwarding plane, my work includes developing network telemetry functionality using P4 on Tofino chips.
At the moment, I am particularly interested in the following areas:
* Congestion control algorithm design in cloud networking.
* Self-Driving Network based on machine learning techniques.
* The application of Software-Defined Networking (SDN) principles in the context of the Internet of Things (IoT). 


# Work experience
* China Mobile Limited: Software Engineer  2023.01-now
    * I was responsible for the design and development of a solution for network telemetry implementation on programmable devices (Tofino). 
      The main focus of this project was to perform telemetry marking on specific five-tuple data flows using the DTEL (Data Plane Telemetry) module. 
      The collected telemetry data includes current device queue depths, in/out timestamps, in/out ports, and the device id. 
      This data is then reported to the control system, which analyzes congestion and path information of the links.
      If congestion is detected on a link, the control system instructs the sending end OVS (Open vSwitch) to apply throttling measures to alleviate network congestion in the data link.
    * I was responsible for collaborating with external vendors to develop network telemetry solutions based on ASIC chips (Broadcom and Centec). 
      This involved devising plans for telemetry implementation using the specified chips and ensuring the overall project progress and successful completion. 
      Additionally, I oversaw the acceptance testing and validation processes to ensure the effectiveness and functionality of the implemented telemetry solutions.
* H3C([Intro](https://youtu.be/DUJ1-CbbLM8?t=33)): Software Engineer  2018.12-2023.01
    * I was responsible for the analysis, design, and development of the simulation network verification module in the AD-DC 5.3 Intent Network Construction project. 
      The main functionality of this project was to capture the quantities of various role devices and network topologies from the intended network design. 
      After confirming the intent, an expert network configuration would be generated.
      In my role, I focused on validating the effectiveness of the network construction. This primarily involved verifying the connectivity of the Underlay network. 
      The specific functionalities included detecting connectivity paths between devices and displaying all these paths on the user interface. 
      Additionally, the module identified potential issues such as loops, route blackholes, and also performed checks on OSPF neighbors.
    * I participated in the development of the AD-DC SeerFabric project, an intelligent lossless data center solution. The project was built upon technologies like PFC (Priority Flow Control), ECN (Explicit Congestion Notification), 
      and other congestion control techniques to avoid congestion hotspots and optimize network paths.
      The DC controller primarily focused on providing automated construction of VLAN networks and distributing ROCE (RDMA over Converged Ethernet) policies. 
      It offered two approaches for PFC/ECN parameter optimization: using expert experience and collaborating with an intelligent analyzer.
      In this project, my main responsibility was to handle the deployment process of the ROCE expert policies. I also participated in the integration and coordination work with the intelligent analyzer to ensure the smooth communication between the various components of the system.
    * I participated in the development of the Telemetry Visualization Configuration project at China Electronics Aeroengine Control System Co., Ltd (CEACS). The main objective of this project was to enable the SDN (Software-Defined Networking) controller to perform the configuration, modification, querying, and clearing of device data collection protocols such as gRPC, ERSPAN, and INT. This functionality aimed to replace the cumbersome process of manually logging into individual devices for command configuration, making it more convenient and efficient.
      The project's key feature was to facilitate the configuration and display of critical data collection and monitoring protocols of relevant devices in the SeerAnalyzer (also known as "SeerAnalyer") intelligent analyzer. 
      The visualization capabilities offered by the Telemetry Visualization Configuration project improved the overall management and monitoring of devices, enhancing the efficiency and effectiveness of the entire network system.

# Eduction
- 2015.9 - 2018.6: M.Eng. in Control Engineering, Jiangnan University. 
- 2011.9 - 2015.6: B.Eng. in Automation, Nanjing Institute of Technology.

# Certificates
* Software Design Engineer of Qualification Certificate of Computer and Software Technology Proficiency
* CET-6
