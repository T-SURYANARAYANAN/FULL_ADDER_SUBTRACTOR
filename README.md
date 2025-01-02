### Name : T-SURYANARAYANAN
### REG NO : 24900450
### EX-04 : Implementation of Full Adder and Full Subtractor



### AIM:

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

### Full Adder and Full Subtractor

### Full Adder

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

### Figure -1 FULL ADDER

### Full Subtractor

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

### Truthtable :

#### Full Adder
![image](https://github.com/user-attachments/assets/4aff2574-3203-4e37-8148-118a0f82bb25)


#### Full Subtractor
![image](https://github.com/user-attachments/assets/51bcc16f-b772-4f54-b682-951d6f20cf6d)


### Procedure
#### Full Adder:
1.Open Quartus II and create a new project.
2.Use schematic design entry to draw the full adder circuit. 
3.The circuit consists of XOR, AND, and OR gates. 
4.Compile the design, verify its functionality through simulation. 
5.Implement the design on the target device and program it.

#### Full Subtractor: 
1.Follow the same steps as for the full adder. 
2.Draw the full subtractor circuit using schematic design. 
3.The circuit includes XOR, AND, OR gates to perform subtraction. 
4.Compile, simulate, implement, and program the design similarly to the full adder.
  

### Program:

#### Full Adder
  ![image](https://github.com/user-attachments/assets/a623f183-23a6-4e18-bb4f-a469394d7ad6)

#### Full Subtractor

![image](https://github.com/user-attachments/assets/3f1f8ddb-bfb4-417d-b920-d44981a91c77)


### RTL Schematic
#### Full Adder
![image](https://github.com/user-attachments/assets/9603d5d7-6c56-4885-8b25-0d1c7440fe3c)

#### Full Subtractor
![image](https://github.com/user-attachments/assets/d908d506-4fcd-4d77-afc8-b7fd6b222be3)

### Output Timing Waveform

#### Full Adder
![image](https://github.com/user-attachments/assets/6751e031-010b-45a3-b49e-6e5ab00af69e)

#### Full Subtractor
![image](https://github.com/user-attachments/assets/8a0b03de-25a5-4072-b6ee-e13eb15df76b)


### Result:

The Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software successfully implemented.



