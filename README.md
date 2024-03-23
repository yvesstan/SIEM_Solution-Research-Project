# Research-Lab
Focus on an open source SIEM to proactively monitor, detect , analyze and respond to real world attacks.

## Objective

This research mainly focus on Detection and Response Lab project aimed to establish a controlled environment for simulating and detecting cyber attacks. The primary focus was to ingest and analyze logs within an open source  Security Information and Event Management (SIEM) system, generating test telemetry to mimic real-world attack scenarios, monitor our environment to detect those attacks and proactively respond and mitigate various threats . This hands-on experience was designed to deepen understanding of network security, attack patterns, and defensive strategies.

##  GENERAL CONTEXT OF THE RESEARCH

Nowadays we live in a world where with the advent of technology most activities are focused on information and data. As a result, faced with the voluminous quantity of these elements and their crucial role in most sectors of activity, the complexity of IS in turn becomes quite vast and heterogeneous (applications, transactions, exchanges, users, BYOD, etc.). ) then widening the attack surfaces, hence increasing the number of vulnerabilities on the information system, whether at the level of design, implementation or even communication protocols.
Consequently, we are witnessing on a daily basis a considerable increase in attacks on networks and computer systems due to the accessibility of tools, whether hardware or software, adapted and easy to use almost everywhere allowing us to attack and exploit vulnerabilities in sight. prevent the proper functioning of the information system. It is with this in mind that the need for fairly sophisticated and daily updated tools is essential! in order to be able to overcome these types of problems and considerably reduce the risks linked to information security.

## RESEARCH PROBLEM
Security breaches are accompanied by significant financial losses and sometimes reputation can be even worse. IT security has become one of the major concerns for businesses today. As computer attacks become more and more widespread, companies no longer wonder if they will be attacked. Rather, they wonder when these will occur.

Despite some measures taken by the company, the network is not safe from intrusions or threats of attacks known to corporate networks, because in IT security, zero risk does not exist; total security cannot be guaranteed. Certainly, firewalls like the one set up in the company network can partially reduce these risks. However, a network protected by a firewall still remains penetrable since a threat can access the network through it, which is an important problem to manage. But that's not all. Archive traces, logs and other circumstantial data from security equipment, ensure the correlation between the different events produced within a structure, generate dashboards and reports following the different events: these are the different tasks that perform most security systems separately. The concern is that completing these separate tasks requires a lot of work. For example, it will be necessary to analyze the events of each piece of equipment and then merge them in order to have an overview of these events. This leads to questions like these: How to respond to these different tasks in one go and basic needs through a single system instead of several? How do you know who is attacking the company's computer system? When did the attack take place? How was the attack carried out? And what to do in the event of an intrusion? In short, how can the company protect itself from intrusions and/or threats of attacks in order to protect its confidential information? How can we have centralized management of all the company's security equipment (firewalls, intrusion detection and prevention systems, etc.) and its entire information system?

With this in mind, research was carried out in order to propose a system which will make it possible to collect in real time events from the various equipment present within the company, to monitor the activities taking place in the network in order to detect possible intrusions and threats to protect our business.

## SPECIFIC RESEARCH OBJECTIVES

The general objective of the project is to generally improve the company's security system, through the implementation of Wazuh which is an open source system allowing us to manage information and security events within the company. an information system. The main ideology is to use a system that is free to provide quality services but above all at lower cost.



## METHODOLOGICAL APPROACHES

After an in-depth study and analysis of the objectives and expected results, the implementation of a security information and event management system or S.I.E.M. (Security Information and Event Management) will attract attention. The methodological approach followed is this: after a bibliographic research to study the generalities, the existing solutions and the different necessary tools, we carried out an analysis of the company's network architecture with a view to proposing one. new for the implementation of the chosen solution. Finally, we will set up a functional test solution in a virtual environment.

## EXPECTED RESULTS

At the end of the project, the system adopted should make it possible to:

· have an overview and centralized management of all the company's IT equipment;
 
· have reports relating to events that have occurred in the company's information system;

· have security alerts after combining data from different security systems;

· continuously monitor the company's information system, particularly in terms of security;

· optimize the security of the company’s IT system


### Skills Learned

- Advanced understanding of SIEM concepts and practical application.
- Proficiency in analyzing and interpreting network logs.
- Ability to generate and recognize attack signatures and patterns.
- Enhanced knowledge of network protocols and security vulnerabilities.
- Development of critical thinking and problem-solving skills in cybersecurity.

### Tools Used

- Security Information and Event Management (SIEM) system for log ingestion and analysis.
- Kali linux OS for the attack's simulation.
- Telemetry generation tools to create realistic network traffic and attack scenarios

  

## Steps

### ![DEPLOYMENT METHODS](https://github.com/yvesstan/Research-Lab/blob/main/DEPLOYMENT%20METHODS.pdf)
### ![USE CASES](https://github.com/yvesstan/Research-Lab/blob/main/USE%20%20CASES.pdf)

## Conclusions & Prospects
Cybersecurity is a discipline of primary importance because the information system is an absolutely vital element for any company.
Information technology is becoming more and more embedded in society, the incentives to compromise the security of deployed computer systems are increasing. These cyberattacks can destabilize an institution and cause colossal economic loss.
The dangers of today's cyberattack mean that the relevant question for companies is not whether they will be attacked or not, but when it will happen, which makes upstream protection essential. With an open-source security solution, companies no longer have any excuse against cyberattacks.
The main objective of this work was to set up a solution for centralized management of logs and security events of an information system.
In this project we have set up the WAZUH platform which is both a SIEM and an XDR allowing the collection, processing, storage and finally the visualization of log files. This allowed us to exploit the visualizations and dashboards of the Kibana interface to monitor the state of the network as well as the activity of equipment and machines in order to avoid breakdowns and attacks on the one hand, and save time and money on the other hand.
At the end of our project, we were able to achieve our objectives, i.e. to set up an open source solution allowing the management of the security of our system, our system met our expectations since there was no impact on performance. network and system was noticed.
This implementation was of great importance to us and it served as an arcade that introduced us to the professional world. Especially since it was an opportunity to implement our technical knowledge learned during our studies.
He taught us on a technical level to be better able to protect our guests and to recommend safety measures to others.

From a general point of view, this project has enabled us to acquire considerable knowledge and to improve our ability to communicate, collaborate and adapt to the professional environment.
In terms of perspectives, improvements are possible to increase the performance of this solution, therefore we would like to introduce more components to our system architecture and integrate an intrusion prevention system into our WAZUH tool.
 
We also want to integrate a system that will alert the company's IT system managers by SMS each time a new intrusion, anomaly or attack is detected on the system and also set up a document specifying a set of actions to take when an attack or intrusion is detected by WAZUH. This document will allow better management of incidents listed within the company's computer system.
The addition of other security modules to our solution could also allow the establishment of a defense in depth mechanism in order to harden the security of information systems.
At the end of this work, we were able to acquire knowledge and experience in computer security. Indeed, as part of this work, we have developed our knowledge in the use of free tools and open-source codes. We familiarized ourselves with the free software WAZUH and we learned how to control the various aspects of the computer security by integrating several solutions and by acting vis-a-vis the multiple problems encountered. These achievements can be directly applied to choices of integration and design in the professional environment.
We therefore hope that this project is the beginning of a professional insertion and a guide for all those who are interested in the world of cybersecurity.
