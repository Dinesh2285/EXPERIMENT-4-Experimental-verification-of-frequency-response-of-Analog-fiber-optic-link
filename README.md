
# Exp 4 Experimental verification of frequency response of Analog fiber optic link
# Fiber Optic Link Analysis (660nm)

## AIM
To analyze the relationship between input and received signal of a 660nm fiber optic cable using analog and digital link.

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
3. Make the following connections (as shown in Figure 19):  
   a. Connect the 1KHz sine wave output to emitter 1's input.  
   b. Connect the fiber optic cable between emitter output and detector input.  
   c. Connect detector 1's output to AC amplifier 1 input.  
4. On the board, switch emitter 1's driver to analog mode.  
5. Switch on the power.  
6. Observe the input to emitter 1 (TP5) and the output from AC amplifier 1 (TP28). Verify that both signals are identical.  
7. Vary the frequency between 10 Hz to 1 MHz and observe the output voltage for a constant input voltage of 5V.  
8. Calculate the bandwidth by determining the gain in decibels (dB).  

---

## BLOCK DIAGRAM

<img width="492" height="278" alt="image" src="https://github.com/user-attachments/assets/63494f8b-375a-40b4-9c59-3a2e504dc326" />


---

## TABULATION  
**Transmission through Analog Link**

![WhatsApp Image 2025-11-15 at 23 46 11_0c2e0540](https://github.com/user-attachments/assets/7d7b86a3-8f9b-4256-bd6d-36351ab2b22d)


---

## MODEL GRAPH

<img width="1040" height="800" alt="image" src="https://github.com/user-attachments/assets/31c27f9d-d09b-442f-9966-92a35dcd785e" />


---

## RESULT

Hence the relationship between input and received signal in 660mm fiber optic cable is found using analog link.
