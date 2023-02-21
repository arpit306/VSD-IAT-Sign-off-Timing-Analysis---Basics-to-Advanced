# VSD-IAT: Static Timing Analysis - Basics to Advanced
![flyer](https://user-images.githubusercontent.com/68592620/220321874-458e55b3-e193-4734-8070-2a2477eaca27.png)  
STA stands for Static Timing Analysis. It is a method to verify the timing correctness of a chip. It evaluates the delays of each timing path in a digital circuit incurred when a signal propagates through it. By this delay calculation, it is able to determine whether the chip meets or violates the timing constraints. In this workshop we studied the concepts involved in STA from basics to advanced, with the help of open source STA tools and libraries.  
## Table of contents  
- [Abstract](https://github.com/arpit306/VSD-IAT-Sign-off-Timing-Analysis---Basics-to-Advanced#%EF%B8%8F-abstract)  
- [Day-1 Lab](https://github.com/arpit306/VSD-IAT-Sign-off-Timing-Analysis---Basics-to-Advanced#%EF%B8%8F-day-1-labs)  
- [Day-2 Lab](https://github.com/arpit306/VSD-IAT-Sign-off-Timing-Analysis---Basics-to-Advanced#%EF%B8%8F-day-2-labs)  
- [Day-3 Lab](https://github.com/arpit306/VSD-IAT-Sign-off-Timing-Analysis---Basics-to-Advanced#%EF%B8%8F-day-3-labs)  
- [Day-4 Lab](https://github.com/arpit306/VSD-IAT-Sign-off-Timing-Analysis---Basics-to-Advanced#%EF%B8%8F-day-4-labs)  
- [Day-5 Lab](https://github.com/arpit306/VSD-IAT-Sign-off-Timing-Analysis---Basics-to-Advanced#%EF%B8%8F-day-5-labs)  
- [Acknowledgement](https://github.com/arpit306/VSD-IAT-Sign-off-Timing-Analysis---Basics-to-Advanced#%EF%B8%8F-acknowledgement)  
- [Author](https://github.com/arpit306/VSD-IAT-Sign-off-Timing-Analysis---Basics-to-Advanced#%EF%B8%8F-author)  
## Abstract
In this 5 days workshop we have used open-source sign-off timing analysis tool STA and open-source Sky130 libraries, to perform the day-wise labs.
Each day has a specific set of task to be completed under this workshop. Following is the detailed proof of work of labs of each day.
## 🔲 Day-1 Lab
[Objective]: To understand the inputs to openSTA and run script commands.
### [1.] Verilog netlist simple.v (Input to openSTA)  

![netlist](https://user-images.githubusercontent.com/68592620/220353404-723d68a1-4de2-4ee3-b1f7-e4fcf369775b.png)

### [2.] Library sky130_fd_sc_hd_tt_025C_1v80.lib file (Input to openSTA)  

![lib](https://user-images.githubusercontent.com/68592620/220355039-9e47d857-4b05-45e5-a8d1-637ce6fd7064.png)

### [3.] SDC constraint simple.sdc file (Input to openSTA)  

![sdc](https://user-images.githubusercontent.com/68592620/220356373-7fd75b3a-a8c1-48d0-96ab-61cacaeff1a8.png)

### [4.] openSTA run script results  

![ss1](https://user-images.githubusercontent.com/68592620/220359535-2033b06a-e4a5-4b40-b07a-fc21d7a87f5b.png)
![imgonline-com-ua-twotoone-knK5JymMuYhlz4zf](https://user-images.githubusercontent.com/68592620/220359573-fde7b9d0-7722-410f-88c1-5959a6f90460.jpg)
## 🔲 Day-2 Lab  
[Objective]: To understand liberty files, SPEF, timing reports.  

### [1.] Following are all the cells present in simple_max.lib  
![cells](https://user-images.githubusercontent.com/68592620/220416066-1e3a1364-1bc3-48e0-b243-989a66415004.png)

### [2.] Number of pins in cell NAND2_X1 in simple_max.lib  
``` There are three pins in NAND2_X1 in simple_max.lib as mentioned below  
    pin 'o'
    pin 'a'
    pin 'b'  
 ```  
### [3.] Difference between NAND2_X1 and NAND3_X1  
 I have observed the following differences between the two.
- First is the **number of input pins** both have. 
![diff1](https://user-images.githubusercontent.com/68592620/220427348-3ca46e3b-6424-4574-8ea4-7be526fdb599.png)

- Second is the difference in **maximum output capacitance.**  
![diff2](https://user-images.githubusercontent.com/68592620/220427504-9bace579-bab1-46b7-b8a6-cdc936619720.png)

- Third is the difference of the **transition times and delays.**
## 🔲 Day-3 Lab
## 🔲 Day-4 Lab
## 🔲 Day-5 Lab
## Acknowledgement

- [Kunal Ghosh](https://github.com/kunalg123), Co-founder of VLSI System Design (VSD) Corp. Pvt. Ltd.
- [Vikas Sachdeva](https://vlsideepdive.com/), Advisor, Tech and VLSI Coach, Trainer and Innovator at vlsideepdive.
## Author

[Arpit Sharma](https://www.linkedin.com/in/arpit-s-a92647108/), B.Tech (2019-23), IPEC, Sahibabad, Delhi-NCR, India  
Contact: arpitniraliya306@gmail.com, 1900300310018@ipec.org.in  <br>
