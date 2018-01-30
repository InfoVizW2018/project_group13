# Real-time Attacks Visualization on Honeypots

**Group 13**: Adeshina ALANI, Abdoul-Djawadou SALAOU, Jorin Weatherston, Rhys Lawson 

## Introduction

Various forms of attacks exist in computer network security in which a honeypot framework can be used to strengthen the security of the network by enticing attackers into the honeypot network. Attackers first gather information about a target by using port scanning techniques in order to identify vulnerabilities in the network and therefore, are able to exploit it. These actions usually result in the form of a scan attack from the attackers. However, the honeypot is setup within the network with the aim to react on the possible security bridges has shown a great value from the security operation perspective. Shown in Figure 1 is a typical computer network with a honeypot setup for enticing and motivating the attackers actions.

<img src="https://lh3.googleusercontent.com/5Y0ao6APPzkOUOvjZ4qA49ynJlwS55izwamSF-oNEv-KVCGJm8h95GdpyQASYaG9MF1GueON1PLxSFAZmFljdbHu-6xHUotKGwYByESPhYxeMI1I2xdbTJ6R_uVKXSLTAe3wei_M" style="zoom:50%">

## Motivation

Attack patterns are not obvious when you look at massive quantities of raw data. One has to cleanse the data and map statistics over the significant attributes in order to make it useful information. Visualization of such processes should help optimize the analysis and highlights patterns to save time. In addition, there is a temporal component to the data. Hence the animation of the data helps analysts understand how the attacks evolve.

## Research Question

The main research question is “*What are the best visualization methodologies for highlighting the real-time behaviours of malicious attackers within honeypot networks*”. This is further broken down into the following individual questions as shown below.

- Which destination ports/services are frequently scanned?
- What are the distribution of ports on the host(target)?
- Which ports are mostly attacked and from which location?
- Which location does a traffic usually originate from mostly (traffic usually originate from the source ports to which location)
- Which date of the week do we have various frequency of scan attack
- What are the frequency of attack per time in each of the unique locations?

In order to address the above questions, we have to make some specific assumptions such as:

- All data that shows up in a honeypot is malicious. 
- Incoming data is optimized for visualization by the attack detection system.
- Visualization will only handle data that has been preprocessed.

In that regard, our project is to extensively analyse and visualize the honeypot dataset obtained from a real time simulation attack on a staged computer network. In order to see various kinds of behaviour about the attackers based on the above questions.

## Approach

In order to address the above questions, we will be using the following methods such as:L

- iterature review on  Honeypots Visualizations 
- Design study following Who/What/How process to ensure design validity of the questions.
- Implementation of visualization dashboard to answer the highlighted questions.

Initial candidate visualizations could combine 

- Real-time node-edge graphs of network and traffic activity 
- Real time line graphs of network trends
- Heatmaps of network ports that highlight attacked ports
- An intelligent network packet explorer to dive into details
- Implementation of data simulator, and visualization candidates in webpage

## Risks

The following  are some of the challenges in delivering a real time visualization 

- Legal access into a live Network
- The data could be massive in very small time-spans (8Tb/hr) making processing and visuals difficult.
- Highlighting the most important data is situational, depending on company and context
- Accessing realistic, or simulating realistic, attack data accurately



##### Key words:

Honeypot Visualization = Cyber-security + Data Analysis + Information Visualization
