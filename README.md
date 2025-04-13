# EXP.NO.1-EXPERIMENTAL-VERIFICATION-OF-VARIOUS-TYPES-OF-SAMPLING-TECHNIQUES
 

1.Experimental Verification Of Signal Sampling Using Various Types Such as 
    i) Natural Sampling
    ii) Flat Top Sampling

## AIM
 To perform experimental verification of various types of sampling such as i)Natural sampling and ii)
 Flat top sampling.
## APPARATUS REQUIRED
Trainer Kit, DSO(10MHz) , Patch Cords and Power Supply (0-30V)   
## PROCEDURE
```
Natural Sampling
1.Refer to the block diagram and carry out the following connections and switch setting.
2.Connect power supply in proper polarity to the kit DCL-10 and switch it on.
3.Connect the 1khz, 5Vpp sine wave signal generated on board to the BUF IN post of the buffer.
and the BUF OUT part of the buffer to the IN post of the flat top sampling block by means of the connecting chords provided.
4.Connect the sampling frequency clock in the internal mode INT clk using switch (Sw4).
5.Using clock selector switch (S1) select 8khz sampling frequency.
6.Using switch (Sw2) select 50% duty cycle.
7.Connect the OUT post of the flat top sampling block to the input IN1 of the second order low pass Butterworth filter and take necessary observations as mentioned below.
8.Repeat the procedure for the 2khz sine wave signal as input.

FLAT TOP SAMPLING:
1.Refer to the block diagram and carry out the following connection and switch setting.
2.Connect power supply in proper polarity to the kit DCL-01 and switch it on.
3.Connect the 1khz, 5Vpp sine wave signal generated on board to the BUF IN post of the buffer and the BUF OUT part of the buffer to the In post of the flat top sampling block by means of the connecting chords provided.
4.Connect the sampling frequency clock in the internal mode INT clk using switch (Sw4).
5.Using clock selector switch(S1) select 8khz sampling frequency.
6.Using switch (Sw2) select 50% duty cycle. Connect the OUT post of the flat top sampling block to the input IN 1 of the second order low pass Butterworth filter and take necessary observation as mentioned below.
7.Repeat the procedure for the 2khz, sine wave signal as input
```
## CIRCUIT DIAGRAM
![Screenshot 2025-04-13 213755](https://github.com/user-attachments/assets/5ed2338a-b804-4028-8960-f2d6c86390d8)

## MODEL GRAPH
![Screenshot 2025-04-13 213821](https://github.com/user-attachments/assets/1292f93b-869f-4022-9810-9c959c0f7994)

## TABLE
![dc hardware exp-1 table](https://github.com/user-attachments/assets/75aaf57a-7089-41ef-9311-ccdc6b26eafc)

## OUTPUT GRAPHS
![dc hardware exp-1](https://github.com/user-attachments/assets/6e65a1b8-a58a-4be6-8bb3-d423f723ef06)
![dc hardware exp-1 graph](https://github.com/user-attachments/assets/135e45f1-e6a2-47ac-b858-b994c59c3dab)

## RESULT 
Thus the sapmpling and reconstruction of the given input signal is done using different types of sampling techniques.
