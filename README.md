# Phase-Locked Loop
This repository shows the design of conventional PLL using Synopsys Custom Compiler at 28nm CMOS technology.

# Table of Contents  
* [Abstract](url)  
* [Introduction](url)  
* [Circuit Details](url)  
* [Circuit Design and Simulation](url)  
* [References](url)  

# Abstract  
The prime focus of this paper to design a conventional PLL with low power consumption and low area. The design is to be implemented in 28nm CMOS technology. Usulally as technology scale down a PLL with wide tuning range, low jitter, and PLL operating at high frequencies are preferred.  

# Introduction  
A phase-locked loop or PLL is a closed loop feedback circuit comprises of four main blocks phase frequency detector (PFD), charge pump (CP), low pass filter (LPF) and voltage-controlled oscillator (VCO) PLL as shown in Fig.1. These blocks are connected to form a closed loop feedback network so as to synchronize the output with the input in both phase and frequency. And this loop continues to run until PLL locked condition is achieved i.e., either zero or constant phase difference between the reference input and the feedback pulse from the output of PLL. PLL is castoff as on chip clock generator, frequency synthesizer and clock and data recovery system in radio, computers and telecommunication system. In general, as technology scale down a PLL with wide tuning range, low jitter, and PLL operating at high frequencies are preferred.  
![image](https://user-images.githubusercontent.com/100137736/155059429-7cd2c6eb-b655-41fb-8309-7c4932ab22d1.png)    Fig. 1. PLL Block Diagram
  




