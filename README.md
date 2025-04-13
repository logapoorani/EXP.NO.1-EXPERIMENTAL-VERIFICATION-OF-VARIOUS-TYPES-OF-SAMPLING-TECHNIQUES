# EXP.NO.1-EXPERIMENTAL-VERIFICATION-OF-VARIOUS-TYPES-OF-SAMPLING-TECHNIQUES
 

1.Experimental Verification Of Signal Sampling Using Various Types Such as 
    i) Natural Sampling
    ii) Flat Top Sampling

## AIM
 To perform experimental verification of various types of sampling such as natural sampling and flat top sampling.
## APPARATUS REQUIRED
Trainer Kit, DSO(10MHz) , Patch Cords and Power Supply (0-30V)   
## PROCEDURE
```
Natural Sampling
1.Refer to the block diagram and carry out the following connections and switch setting.
2.Connect power supply in proper polarity to the kit DCL-10 and switch it on.
3.Connect the 1khz, 5Vpp sine wave signal generated on board to the BUF IN post of the buffer.
4.and the BUF OUT part of the buffer to the IN post of the flat top sampling block by means of the connecting chords provided.
5.Connect the sampling frequency clock in the internal mode INT clk using switch (Sw4).
6.Using clock selector switch (S1) select 8khz sampling frequency.
7.Using switch (Sw2) select 50% duty cycle.
8.Connect the OUT post of the flat top sampling block to the input IN1 of the second order low pass Butterworth filter and take necessary observations as mentioned below.
9.Repeat the procedure for the 2khz sine wave signal as input.

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
![Screenshot 2025-04-13 213755](https://github.com/user-attachments/assets/d58775bf-7d80-41c0-8b75-0f8ca6fd03d1)

## MODEL GRAPH
![Screenshot 2025-04-13 213821](https://github.com/user-attachments/assets/5f90e44b-d4f8-4af7-b9da-9ac248455093)

## TABLE
![dc hardware exp-1 table](https://github.com/user-attachments/assets/8bb9bbe3-9fc4-47f9-aaa2-1948e2a1c4e1)

## OUTPUT GRAPHS
![dc hardware exp-1](https://github.com/user-attachments/assets/51d5d372-79a7-4d46-bae9-3e255a387165)
![dc hardware exp-1 graph](https://github.com/user-attachments/assets/b203871e-c2e8-45c2-8b2c-e363ce6708b0)

## RESULT 
Thus the sapmpling and reconstruction of the given input signal is done using different types of sampling techniques.
