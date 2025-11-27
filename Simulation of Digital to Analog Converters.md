## EC1421-19EC421-Analysis-and-Design-of-Analog-ICs
## SIMULATION OF SCHMITT TRIGGER

## AIM:
To Design and simulate the digital to analog converter (DAC) circuit using LT Spice

## SOFTWARE REQUIRED:
LT-Spice

## PROCEDURE:
1. Double click on LT Spice icon.

2. New schematic window open.

3. Pick and paste the required component from the library and draw the circuit diagram .

4. Complete the connection.

5. Select 1 voltage and select pulse width as 
Vinitial [V]: 5
       Von [V]: 0
       Tdelay [s]: 0
       Trise [s]: 1u
       Tfall [s]: 1u
               Ton [s]: 10m
        Tperiod [s]: 20m
        Ncycles: 100
Change the values of Ton = 20m , 40m, Tperiod  = 40m , 80m
For v2 and v3  keeping the other values constant.
6. Save the file by giving file name.

7. Click on the run option -->click advanced open -->select select transient analysis -->enter the amplitude time delay stop time value as (.tran 0 200 0 0.01).

8. Click on the run option -->simulation window opens-->place the probe -->output graph is obtained.

## CIRCUIT DIAGRAM:
### DAC:
![WhatsApp Image 2025-11-27 at 18 36 01_c0521564](https://github.com/user-attachments/assets/e4e81d4f-106f-4cf0-875a-3f50a7eb15a4)


## OUTPUT GRAPH:
### DAC:
![WhatsApp Image 2025-11-27 at 18 36 01_cc368c8c](https://github.com/user-attachments/assets/031262e1-a042-4bc3-997c-d256f5b95ba2)

![WhatsApp Image 2025-11-27 at 13 59 00_51deda10](https://github.com/user-attachments/assets/d596afe2-64e1-4ae3-8532-014eccceaf7e)

## RESULT:
Thus the LT-SPICE tool has been studied and digital to analog converter (DAC) circuit is simulated.
![WhatsApp Image 2025-11-27 at 13 59 00_51deda10](https://github.com/user-attachments/assets/431c1197-2754-4991-8ef9-f888461ee256)
