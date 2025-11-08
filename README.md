# Simplified AMBA AHB

AMBA (Advanced Microcontroller Bus Architecture) is a communication standard developed by ARM to connect different parts of a System-on-Chip (SoC), like CPU, memory, and input/output devices. One of the most important buses in AMBA is the AHB – Advanced High-performance Bus.
The AMBA AHB is used when fast data transfer is required. It connects high-speed components such as processors, on-chip memory, and DMA controllers. In this bus system, only one master can use the bus at a time to communicate with a slave device. The communication is controlled using signals like address, data, and control signals.
The designed AHB bus uses features like single clock operation, which help in transferring data quickly and efficiently. Because AMBA AHB follows a standard format, it becomes easier to design systems and reuse the same blocks in other projects.

<img width="653" height="312" alt="image" src="https://github.com/user-attachments/assets/ff28fdce-030d-49ca-bbba-af1f0186400c" />


<img width="643" height="381" alt="image" src="https://github.com/user-attachments/assets/29e9e175-6608-44b0-beaa-b0589042b22e" />

<img width="599" height="286" alt="image" src="https://github.com/user-attachments/assets/b58a980c-fc9a-4342-8c7c-fa75e86c4971" />


Reference: 
[1]	P. Giridhar and P. Choudhury, "Design and Verification of AMBA AHB," 2019 1st International Conference on Advanced Technologies in Intelligent Control, Environment, Computing & Communication Engineering (ICATIECE), Bangalore, India, 2019, pp. 310-315, doi: 10.1109/ICATIECE45860.2019.9063856. keywords: {Decoding;Microcontrollers;Multiplexing;Automata;Standards;System-on-chip;Protocols;AHB;AMBA-AHB;QuestaSim;ARM}

[2]	L. Deeksha and B. R. Shivakumar, "Effective Design and Implementation of AMBA AHB Bus Protocol using Verilog," 2019 International Conference on Intelligent Sustainable Systems (ICISS), Palladam, India, 2019, pp. 1-5, doi: 10.1109/ISS1.2019.8907975. keywords: {Microcontrollers;Hardware design languages;System-on-chip;Clocks;Registers;Conferences;Computer architecture;Advanced Microcontroller Bus Architecture;Advanced High-performance Bus;System-on-Chip;Hardware Description Language}
