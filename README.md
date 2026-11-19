# EXPERIMENT--01-ALP-FOR-8086
Name : MARXIN LIJO M

REG NO: 212223240085 

Date of experiment :12-11-2026



## Aim: To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 ## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	  Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
 
 
3.		write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 

4.	 Compile the program and check for the errors 
5.	Run (once there is no syntax error) 

6.	Click OK to see/view the output of your program on the Emulator screen. 


7.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,
8.	 


![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)











9.	Click on emulate to start emulation 








![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)








10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 






![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)







## Programs for arithmetic  operations

## Addition  of 8 bit ALP 

```asm
ORG 100H

MOV AX, 0005H
MOV BX, 0003H
ADD AX, BX
MOV [1200H], AX
HLT
```

## Output  
 <img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/dfc1c1f1-e149-4411-ba2f-44dc72e5b714" />

## Subtraction   of 8 bit numbers  ALP 
 ```asm
ORG 100H

MOV AX, 0009H
MOV BX, 0004H
SUB AX, BX
MOV [1200H], AX
HLT
```

## Output 

<img width="1917" height="1143" alt="image" src="https://github.com/user-attachments/assets/a31f5a6c-74fd-4fb8-ac88-0e4086415996" />

## Multiplication alp 
```asm
ORG 100H

MOV AX, 0005H
MOV BX, 0003H
MUL BX
MOV [1200H], AX
HLT
```
 ## Output  

<img width="1917" height="1142" alt="image" src="https://github.com/user-attachments/assets/3148ae73-54ec-401b-89db-3125d8bbbbda" />

## Division alp 
```asm
ORG 100H

MOV AX, 0014H
MOV BX, 0004H
MOV DX, 0000H
DIV BX
MOV [1200H], AX
HLT
```
## Output  

<img width="1917" height="1116" alt="image" src="https://github.com/user-attachments/assets/8ffe29f2-96b5-4062-ab8e-5d1a01586919" />

## AND Operation of 8 bit numbers ALP

```asm
ORG 100H

MOV AX, 000CH
MOV BX, 000AH
AND AX, BX
MOV [1200H], AX
HLT
```

## Output

<img width="1917" height="1137" alt="image" src="https://github.com/user-attachments/assets/bab15203-f6ed-4044-8ad0-df77ef51d0ab" />


## OR Operation of 8 bit numbers ALP

```asm
ORG 100H

MOV AX, 000CH
MOV BX, 000AH
OR AX, BX
MOV [1200H], AX
HLT
```

## Output

<img width="1915" height="1137" alt="image" src="https://github.com/user-attachments/assets/cdc433b3-e9e1-46d5-9b91-9208824671f8" />



## NOT Operation of 8 bit numbers ALP

```asm
ORG 100H

MOV AX, 000FH
NOT AX
MOV [1200H], AX
HLT
```

## Output

<img width="1917" height="1137" alt="image" src="https://github.com/user-attachments/assets/fe7eec77-c99c-4841-9c42-ed669a096d39" />



## XOR Operation of 8 bit numbers ALP

```asm
ORG 100H

MOV AX, 000CH
MOV BX, 000AH
XOR AX, BX
MOV [1200H], AX
HLT
```

## Output
<img width="1915" height="1118" alt="image" src="https://github.com/user-attachments/assets/af925cbb-db0d-411d-9e53-fab77663c42b" />


## Result :
 The execution of ALP on fundamental arithmetic and logical operations is completed successfully.








