
Exp 5 Experimental verification of frequency response of Digital fiber optic link
# Digital Fiber Optic Link Analysis (600nm)

## AIM
To analyze the relationship between input and received signal of a 600nm fiber optic cable using digital link.

---

## EQUIPMENTS REQUIRED
- Fiber optic trainer kit ST 2502  
- Power supply  
- Patch cords  
- CRO (Cathode Ray Oscilloscope)  
- 660 nm fiber cable  

---

## THEORY

Fiber optic links can be used for transmission of digital as well as analog signals. A fiber optic link typically consists of three main elements:
- **Transmitter**: Converts the electrical input signal into optical (light) energy.
- **Optical Fiber**: Serves as the transmission medium for the light signal.
- **Receiver**: Converts the received light back into an electrical signal, preserving the original signal pattern.

---

## PROCEDURE

1. Connect the power supply to the board.  
2. Ensure that all switched faults are set to ‘Off’.  
3. Make the following connections:  
   a. Connect the 1 KHz square wave output to emitter 1's input.  
   b. Connect the fiber optic cable between emitter output and detector input.  
   c. Connect detector 1's output to comparator 1’s input.  
   d. Connect comparator 1's output to AC amplifier 1's input.  
4. On the board, switch emitter 1's driver to digital mode.  
5. Switch on the power.  
6. Monitor both the inputs to comparator 1 (TP13 & TP14). Slowly adjust the comparator's bias preset until the DC level on TP13 lies midway between the high and low levels of the signal on TP14.  
7. Observe the input to emitter 1 (TP5) and the output from AC amplifier 1 (TP28). Verify that both signals are identical.  
8. Vary the frequency between 10 Hz to 1 MHz and observe the output voltage for a constant input voltage of 5V.  
9. Calculate the bandwidth by determining the gain in decibels (dB).  

---

## BLOCK DIAGRAM

<img width="526" height="199" alt="image" src="https://github.com/user-attachments/assets/b220b584-a50e-4151-b8ba-5f9939f09007" />


---


## CONNECTION DIAGRAM  
**Setting up a Digital Link**

<img width="514" height="135" alt="image" src="https://github.com/user-attachments/assets/cf4ac45d-a686-45c0-9c6b-3fbe65453086" />


---

## TABULATION  
**Transmission through Digital Link**

![WhatsApp Image 2025-11-17 at 04 11 54_3767da54](https://github.com/user-attachments/assets/00bf0793-b0fc-4117-b50a-a4a519fcde97)


| Frequency | Output Signal (Vo) | Gain (Vp/Vi) | Gain in dB |
|-----------|---------------------|--------------|-------------|
| 1 kHz     | 3.48 V             | 0.496        | -6.09       |
| 5 kHz     | 4.74 V             | 0.948        | -0.46       |
| 10 kHz    | 9.75 V             | 1.98         | 5.823       |
| 20 kHz    | 11.47 V            | 2.294        | 7.211       |
| 50 kHz    | 12.90 V            | 2.58         | 8.23        |
| 75 kHz    | 12.85 V            | 2.58         | 8.23        |
| 100 kHz   | 10.85 V            | 2.17         | 6.729       |
| 150 kHz   | 8.47 V             | 2.17         | 6.729       |
| 250 kHz   | 5.48 V             | 1.694        | 4.576       |

---

## MODEL GRAPH

<img width="704" height="339" alt="image" src="https://github.com/user-attachments/assets/992b3de5-6186-4aac-b256-e9ae012ba458" />

![WhatsApp Image 2025-11-17 at 04 12 57_a462129b](https://github.com/user-attachments/assets/03735349-7b3d-4c07-92bd-aeb2e7501189)

---

## RESULT

Hence, the relationship between input and received signal of a 600nm fiber optic cable using digital link is verified
