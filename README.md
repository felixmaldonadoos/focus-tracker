Authors: Mario De Lorenzo, Felix Maldonado Osorio

Affiliation: Drexel Hackathon 2022

Date: April 30 - May 1, 2022


# Table of Contents
- [Background](#Background)
- [Goal](#Goal)
- [Methods](#Methods)
- [Focus Tracker](#focus-tracker)
- [Implementation](#Implementation)
- [Future Work](#Future-Work)
- [Sources](#Sources)

# Background 

Current learning patterns rely on generalized methodologies, which recommend to take consistent breaks and compartmentalize active studying and breaks. 
Common include the Pomodoro technique (insert hyperlink) and Desktime study (insert hyperlink). These techniques recommend one to take 5 or 17 minute 
study breaks after 25 or 52 minutes of studying, Pomodoro and Desktime respectively. 

A challenge with this lacking personalized study methodologies. With digital distractions being introduced by remote work, common study patterns may not 
work effectively and apply to everyone, leading to anxiety buildup and burnout (SOURCE). The goal of our project is to develop a signal processing pipeline 
that allows the user to quantify times of active focus during their study time, to maximize learning and decrease stress and burnout. 

-- explain background of EEG -- 

-- explain use of raspberry pi -- 

# Goal
The goal of the project is to develop a signal processing pipeline that can be implemented into an inexpensive embedded system, such as a 
```Raspberry Pi``` and interface with low-cost ```electroencephalography (EEG)``` devices. EEG is a popular brain-imaging tool used to detect electrical activity in the brain.

# Methods
This project utilizes EEG data and ```OpenVibe```, an open-source brain computer interface (BCI) software ([download](http://openvibe.inria.fr/downloads/)), to detect is subject is actively focused. 

EEG offers high temporal resolution (~1 ms) and relatively high spatial resolution (1-3 cm) for detecting surface or deep brain activation (SOURCE). 
For this project the team tested the processing pipeline with a ```Unicorn Hybrid Black 8-Channel ```fs = 250 Hz``` ``` ([product](https://www.unicorn-bi.com/?gclid=Cj0KCQjwvLOTBhCJARIsACVldV1YNGgvgl_TGRFygCgsKmpA0AnJjArZZoUj_heLh7hWoNSNNysdkY8aAhaFEALw_wcB)) and connected to OpenVibe via the ```Lab Streaming Layer (LSL)``` LSL is a network communications protocol that sends EEG data to network and allows for multiple clients to connect and collect streamed data. Many EEG headsets are compatible with LSL, such as ```OpenBCI``` ([product](https://shop.openbci.com/collections/frontpage)), a relatively accessible EEG platform.


# focus-tracker
Develop an EEG platform and user-interface that allows 

# Implementation
# Future Work
# Sources
[1]
[2] 

