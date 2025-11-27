# EC1421-19EC421-Analysis-and-Design-of-Analog-ICs
# DESIGN OF ACTIVE LOW PASS,HIGH PASS AND BAND PASS FILTERS USING OP-AMP 

## AIM: 

To design and obtain the frequency response of 
i) First order Low Pass Filter (LPF) 
ii) First order High Pass Filter (HPF) 
iii) Band pass filter
 
## APPARATUS REQUIRED

<img width="625" height="170" alt="image" src="https://github.com/user-attachments/assets/900fc8b3-3a8c-4208-bf52-98cc9e281e21" />

## THEORY
## LOW PASS FILTER 
 A LPF allows frequencies from 0 to higher cut of frequency, fH.  At fH the gain is 0.707 
Amax, and after fH gain decreases at a constant rate with an increase in frequency.  The gain 
decreases 20dB each time the frequency is increased by 10.  Hence the rate at which the gain 
rolls off after fH is 20dB/decade or 6 dB/ octave, where octave signifies a two fold increase in 
frequency.  The frequency f=fH is called the cut off frequency because the gain of the filter at this 
frequency is down by 3 dB from 0 Hz.  Other equivalent terms for cut-off frequency are -3dB 
frequency, break frequency, or corner frequency.
# HIGH PASS FILTER 
The frequency at which the magnitude of the gain is 0.707 times the maximum value of 
gain is called low cut off frequency.  Obviously, all frequencies higher than fL are pass band 
frequencies with the highest frequency determined by the closed –loop band width all of the op
amp. 
# BAND PASS FILTER 
A band pass filter has a pass band between two cutoff frequencies fH and fL such that fH > 
fL.  Any input frequency outside this pass band is attenuated.  There are two types of band-pass 
filters.  Wide band pass and Narrow band pass filters.  We can define a filter as wide band pass if 
its quality factor Q <10.  If Q>10, then we call the filter a narrow band pass filter.  A wide band 
pass filter can be formed by simply cascading high-pass and low-pass sections.  The order of 
band pass filter depends on the order of high pass and low pass sections.

## CIRCUIT DIAGRAM: 
## LOW_PASS
![WhatsApp Image 2025-11-27 at 13 47 26_5c63fc5c](https://github.com/user-attachments/assets/99b741fa-5ed8-4b66-9658-555978572321)

## HIGH-PASS
![WhatsApp Image 2025-11-27 at 13 49 08_035e7822](https://github.com/user-attachments/assets/267eb16c-c79f-486b-95d1-888c926310ef)

## BAND-PASS
![WhatsApp Image 2025-11-27 at 13 50 53_5eef094d](https://github.com/user-attachments/assets/654f7168-8ba5-44db-94e5-4e9b70074f5a)

## MODEL GRAPH:
## LOW_PASS
![WhatsApp Image 2025-11-27 at 13 47 45_59937a78](https://github.com/user-attachments/assets/8c15a2d8-9720-4024-8eff-f5d607743d1b)

## HIGH-PASS
![WhatsApp Image 2025-11-27 at 13 49 28_18593bf0](https://github.com/user-attachments/assets/a94328f7-99cd-46c5-81f8-6d7f3d63796f)

## BAND-PASS
![WhatsApp Image 2025-11-27 at 13 51 17_04522450](https://github.com/user-attachments/assets/f3cf9ac2-f713-4d55-a955-012ab9e648fb)

## PROCEDURE - (LPF & HPF): 
1. Connect the circuit as shown in the circuit diagram. 
2. Select the corresponding cut-off frequency (higher or lower) and determine the value of C&R. 
select the value of R1 & Rf depending on desired passband gain Af.. 
3. Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp. 
4. Tabulate the output voltage Vo with respect to different values of input frequency. 
5. Calculate passband gain and plot the graph of frequency versus voltage gain & check the 
graph to  get approximately the same characteristic as shown in the model graph. 
# PROCEDURE:BAND PASS FILTER 
1. Select the lower and higher cut-off frequency and calculate the value of R & C for the given 
frequencies. 
2. Design for LPF & HPF separately and then combine the circuit by first placing the HPF 
followed by a LPF (i.e) HPF in series with LPF. 
3. Connect the circuit as shown in the circuit diagram. 
4. Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp. 
5. Tabulate the output voltage Vo with respect to different values of input frequency. 
6. Calculate passband gain and plot the graph of frequency versus voltage gain & check the 
graph to get approximately the same characteristic as shown in the model graph

## DESIGN:LPF & HPF:

<img width="429" height="324" alt="image" src="https://github.com/user-attachments/assets/b0f0ac0a-3006-494c-9096-e91ae2d6e87c" />

# DESIGN: BAND PASS FILTER
Design a BPF to pass a band of 400Hz to 2KHz with a pass band gain of 4.  
1. Select the highest cut-off frequency of LPF as fH = 10 KHz and the lowest cut-off frequency 
of HPF as fL = 1 KHz.  
2. Design the HPF first by taking fL = 1KHz. Assume the value of C < 1μf.  
Let C = 0.1μf.  
3. Calculate R from the expression.  
Given: fH = 2KHz  = 1/ (2πR1C1) 
   Let C1 = 0.1 µF, R1 = 7.9 KΩ 
Given: fL = 400Hz  = 1/ (2πR2C2) 
   Let C2 = 0.1 µF, R2 = 39.8 KΩ 
  Pass band Gain=4 
   Now   Ao = 1 + (Rf / R1)  
               2-1=(Rf / Ri) 
                Ri = Rf 
                 Let  Ri = Rf = 10 KΩ
## TABULATION:
## LOW_PASS
![WhatsApp Image 2025-11-27 at 13 53 08_4400a230](https://github.com/user-attachments/assets/2e75344e-5857-4f23-8152-b285c8691c0d)

## HIGH-PASS
![WhatsApp Image 2025-11-27 at 13 52 26_26919b48](https://github.com/user-attachments/assets/c76493c3-b182-435e-9be0-fa0c94ff83e7)

## BAND-PASS
![WhatsApp Image 2025-11-27 at 13 52 42_ac612976](https://github.com/user-attachments/assets/11e43af0-63eb-471c-9267-e71329c52a54)

## GRAPH:
## LOW_PASS
![WhatsApp Image 2025-11-27 at 13 48 21_52e55f41](https://github.com/user-attachments/assets/1aa0b8ff-fd05-4ba4-9cd3-ded1787919fe)

## HIGH-PASS
![WhatsApp Image 2025-11-27 at 13 50 11_d1cb39a0](https://github.com/user-attachments/assets/a0dc5256-cf15-4a57-879a-2c8be71fe077)

## BAND-PASS
![WhatsApp Image 2025-11-27 at 13 52 06_1d533c26](https://github.com/user-attachments/assets/2f481534-415b-45e0-8907-c4c06cc11cb1)

 ## RESULTS:
Thus an Active Low pass, High pass and Band Pass Filters are designed and 
tested using op-amp IC 741. 

