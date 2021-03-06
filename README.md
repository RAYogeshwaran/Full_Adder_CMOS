# CMOS one bit Full Adder 
This repository presents CMOS one bit adder design made in Synopsys Custom Compiler as part of Cloud Based Analog IC Design Hackathon. 
## Contents
1. Abstract 
2. Introduction
3. Tool Information
5. Circuit Design
6. Symbol
7. Testbench
8. Primewave Simulation
9. Waveforms
10. Netlist
11. Author 
12. Acknowledgements
13. Reference
## Abstract
The CMOS implementation of conventional 1 bit full adder (28T) in Synopsys custom compiler. The circuit is capable of performing addition of two 1 bit numbers considering the carry and produces the sum and carry as output.
## Introduction
The design presented in this repository is a one bit full Adder circuit. Implemented using CMOS design. This circuit takes three inputs namely A, B, Cin and performs its addition and the output is shown with the sum value along with the carry bit. This is a basic and essential circuit for the construction of higher order adders. The adder implemented here is a conventional adder which uses 28 MOS Transistors.  
Truth table of one bit full adder is as follows:  
![image](https://user-images.githubusercontent.com/56624086/156185340-c69b3af7-51a9-4cfc-a404-733eb6f997df.png)  
The Full Adder circuit can be implemented using the Truth Table and K-Map simplification.  
**Sum = A ⊕ B ⊕ Cin  
Carry = A.B + B.Cin + Cin.A**  
  
A Full Adder's circuit can be used as a part of many other larger circuits like Ripple Carry Adder, which adds n-bits simultaneously. The dedicated multiplication circuit uses Full Adder's circuit to perform Carryout Multiplication. Full Adders are used in ALU- Arithmetic Logic Unit.

## Tool Information
The **Synopsys Custom Compiler™** design environment is a modern solution for full-custom analog, custom digital, and mixed-signal IC design. The Custom Compiler design environment includes features for mixed-signal design entry, design debug, simulation management, analysis, and reporting. For layout, Custom Compiler provides fast and user-friendly polygon editing features and boosts productivity with its pioneering visually-assisted automation flow.  
  
The Synopsys 28nm Process Design Kit(PDK) was used in creation and simulation of the above designed circuit.  
  
**PrimeWave™** Design Environment is a comprehensive and flexible environment for simulation setup and analysis of analog, RF, mixed-signal design, custom-digital and memory designs within the Synopsys Custom Design Platform. 

## Circuit Design
![Screenshot (825)](https://user-images.githubusercontent.com/56624086/156175274-59325739-9528-48a1-9107-e1c23cdb9b8e.png)  
In the above design conventional Full Adder Circuit consisting of 28 MOSFETS has been implemetned and the output is labelled as Sum and Carry.  
## Symbol
![Screenshot (826)](https://user-images.githubusercontent.com/56624086/156175416-094231b1-524e-4557-9ea3-1231ed8a8f56.png)  
The Symbol has has pins vdd(supply), ground, A, B, Cin, Sum, Carry.   
## Testbench
![Screenshot (829)](https://user-images.githubusercontent.com/56624086/156175469-5337f4a7-eb14-47ac-9f3d-cf2e4cadcea8.png)  
Pulse voltage has been given to inputs for covering all posible combination. 
## Primewave Simulation
![Screenshot (828)](https://user-images.githubusercontent.com/56624086/156175502-ec6e0229-136f-41ac-b759-034dee84cf68.png)  
The runtime of simulation is 80us which will cover all possible combinations of input.  
## Waveforms
![Screenshot (830)](https://user-images.githubusercontent.com/56624086/156175537-68098ec0-d93d-41a4-9f88-030cac1846ae.png)  
The waveform is as expected from the truth table. Hence the working of circuit is as expected.  
## Netlist
Netlist can be found [here](https://github.com/RAYogeshwaran/Full_Adder_CMOS/blob/main/netlist.txt)
## Author 
R A Yogeshwaran, B.Tech Electronics and Communication, Vellore Institute of Technology, Vellore, Tamil Nadu.
## Acknowledgements
[Kunal Ghosh, Co-founder, VSD Corp. Pvt. Ltd.](https://www.linkedin.com/in/kunal-ghosh-vlsisystemdesign-com-28084836/)  
[IIT hyderabad](https://iith.ac.in/)  
[Synopsys Company](https://www.synopsys.com/)
## Reference
[1] A. K. Yadav, B. P. Shrivatava and A. K. Dadoriya, "Low power high speed 1-bit full adder circuit design at 45nm CMOS technology," 2017 International Conference on Recent Innovations in Signal processing and Embedded Systems (RISE), 2017, pp. 427-432, doi: 10.1109/RISE.2017.8378203.
