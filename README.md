# EXP12: 4 BIT RIPPLE COUNTER
## NAME  : GAYATHRI M
## REGISTRATION NUMBER : 212224050007

### AIM:

To implement 4 Bit Ripple Counter using verilog and validating their functionality using their functional tables

### SOFTWARE REQUIRED:

Quartus prime

### THEORY:

### 4 Bit Ripple Counter

A binary ripple counter consists of a series connection of complementing flip-flops (T or JK type), with the output of each flip-flop connected to the Clock Pulse input of the next higher-order flip-flop. The flip-flop holding the least significant bit receives the incoming count pulses. The diagram of a 4-bit binary ripple counter is shown in Fig. below.

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/cb4b74d4-31ab-4359-95d0-d22e67daba13)

In timing diagram Q0 is changing as soon as the negative edge of clock pulse is encountered, Q1 is changing when negative edge of Q0 is encountered(because Q0 is like clock pulse for second flip flop) and so on.

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/a573a7d6-014e-4e54-93e6-e2ac9530960b)

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/85e1958a-2fc1-49bb-9a9f-d58ccbf3663c)

### PROCEDURE:
 
 1. Type the program in Quartus software.
 2. Compile and run the program.
 3. Generate the RTL schematic and save the logic diagram.
 4. Create nodes for inputs and outputs to generate the timing diagram.
 5. For different input combinations generate the timing diagram



### PROGRAM :

![sc down code](https://github.com/user-attachments/assets/630373c3-f73d-4988-928c-60e9a4c12d67)


### RTL LOGIC :

![sc down logic](https://github.com/user-attachments/assets/57bc25fb-c557-4292-8617-2f4488bbce18)


### RTL OUTPUT :

![exp12 wave](https://github.com/user-attachments/assets/35d60ba4-cf7b-426d-8e26-30bf77ff6152)


### RESULT :

Thus we have implemented and verified 4 Bit Ripple Counter using verilog and validating their functionality using their functional tables 
