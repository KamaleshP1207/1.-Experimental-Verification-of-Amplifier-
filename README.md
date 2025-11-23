#**EX.NO:** 1  # EXPERIMENTAL VERIFICATION OF AMPLIFIER INVERTING, NON INVERTING , DIFFERENTIAL AMPLIFIER AND INSTRUMENTATION AMPLIFIERS

DATE:A.09/08/2025,B.19/08/2025,C.23/08/2025,D.28/10/2025

SLOT:5M1-1
---

## AIM
To design and construct an Inverting, Non-Inverting, Differential and Instrumentation amplifiers.

---

## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 1 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 100K, 10K, 15K, 4.4K, 2K, 20K | 2 |
| 7 | Connecting wires and probes | As required | — |

---

## THEORY

Op-amp in open-loop configuration has limited application due to its enormous open-loop gain. Controlled gain can be achieved by taking a part of the output signal to the input through feedback.  
This is called a **Closed-Loop Configuration**.

The four basic types of closed-loop amplifier configurations are:
- Inverting amplifier  
- Non-inverting amplifier  
- Differential amplifier
- Instrumentation amplifier 

The entire configuration can operate with either AC or DC input.
		
 

---
**A.Inverting Amplifier**

This is the most widely used op-amp configuration.  
The output voltage Vo  is fed back to the inverting input terminal through the  Rf - R1 network.  
The negative sign in gain indicates a **phase shift of 180°**.


Acl = -RF/R1

PIN DIAGRAM
<img width="624" height="269" alt="image" src="https://github.com/user-attachments/assets/635c9837-d5f5-4d6f-acc9-8a47a4368230" />

CIRCUIT DIAGRAM: INVERTING AMPLIFIER:
![WhatsApp Image 2025-11-23 at 17 06 09_bf06992a](https://github.com/user-attachments/assets/ae654196-aa6e-49f5-a443-9f5a971b9116)


MODEL GRAPH 

<img width="543" height="357" alt="image" src="https://github.com/user-attachments/assets/1836d120-768e-454f-bfe4-682ce70ea7a1" />



DESIGN:

Inverting amplifier:

A = -Rf/R1
Take  A = 10
Rf =10 R1
Choose R1 = 10kΩ, Rf=100kΩ

PROCEDURE:
Inverting amplifier:

1.	Select R1 as a constant value and choose a value of Rf.
2.	Connect the circuit as per as the circuit diagram.
3.	Apply the constant amplitude input voltage to the circuit.
4.	Measure the output voltage amplitude for different value of V1 from DSO.
5.	Calculate the practical Voltage for different value of V1 & compare it with theoretical output.
6.	Practical gain & theoretical voltage should be approximately equal.
7.	Plot the graph of the input wave versus output wave for any one practical case.


## TABULATION
![WhatsApp Image 2025-11-23 at 17 12 03_78eaa53d](https://github.com/user-attachments/assets/0337c5ef-7c4d-437b-a17a-d15b28e65737)



---
## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-11-23 at 17 14 44_5576c4d9](https://github.com/user-attachments/assets/fa7750bf-ffb3-4985-a55b-8e7abdfe66d0)


---
### **B.Non-Inverting Amplifier**

If the signal is applied to the non-inverting input terminal without inversion, it is called a **non-inverting amplifier**.  
Here, the output is fed back to the inverting terminal, and **no phase shift** occurs.


ACL = 1 + RF/R1


---

## CIRCUIT DIAGRAM


![WhatsApp Image 2025-11-23 at 17 19 04_fb5881cb](https://github.com/user-attachments/assets/60fa9ad6-d419-497f-a4bc-f7bc86e4b1df)


---

## MODEL GRAPH

<img width="456" height="340" alt="image" src="https://github.com/user-attachments/assets/00c7aaec-b4d8-414e-afa3-e985eb3dd902" />

---
PROCEDURE:
### **For  Non-Inverting Amplifier**
1. Select R1  as a constant value and choose a value for Rf .  
2. Connect the circuit as per the diagram.  
3. Apply constant amplitude input voltage.  
4. Measure the output voltage amplitude for different V1 using DSO.  
5. Compare practical and theoretical values of Vo .  
6. Verify that practical gain ≈ theoretical gain.  
7. Plot the input vs. output waveform for one practical case.

## TABULATION

![WhatsApp Image 2025-11-23 at 17 19 05_ce8807f9](https://github.com/user-attachments/assets/6f32f57c-54db-4ae7-a322-1799aedc90b4)


---
## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-11-23 at 17 25 04_66f71788](https://github.com/user-attachments/assets/949ff1cc-e9b7-4219-b234-22c962c067e8)
![WhatsApp Image 2025-11-23 at 17 25 05_383b9271](https://github.com/user-attachments/assets/6f6b7d9a-8d84-40cd-bf9d-e6f3e6d52a63)


---
**C. DIFFERENTIAL AMPLIFIER**

A circuit that amplifies the **difference** between two input signals is called a **Differential Amplifier**.  
It is useful in instrumentation applications.  
If the two input signals are identical, the output is ideally **zero**.


A = Vo/{V2 - V1} = -Rf/R1
## CIRCUIT DIAGRAM
![WhatsApp Image 2025-11-23 at 17 31 25_ae7b1be2](https://github.com/user-attachments/assets/5b4d5d58-d707-446d-9414-93f346adf8fe)


## MODEL GRAPH
<img width="678" height="334" alt="image" src="https://github.com/user-attachments/assets/6aa1b9dd-b112-4be1-a37a-d5ee19607b1d" />

---

## DESIGN


### **Differential Amplifier**

AV = Vo/{V1 - V2} = -Rf/R1


Take  A = 10 
⇒  Rf = 1R1   
Choose  R1 = 15kOhm, Rf = 15kOhm

---



## PROCEDURE (Differential Amplifier)
1. Select  R1, R2, R3, Rf  such that R1 = R2  and  R3 = Rf .  
2. Connect the circuit as per the circuit diagram.  
3. Apply constant inputs Vin1 and  Vin2 .  
4. Measure output voltage using DSO.  
5. Compare theoretical and practical  Vo .  
6. Verify practical ≈ theoretical output.  
7. Plot the input vs. output waveform.

---

## TABULATION (Differential Amplifier)

![WhatsApp Image 2025-11-23 at 17 31 26_19fc9949](https://github.com/user-attachments/assets/3d7f018b-fc00-435b-88cf-2cdd1e6a4760)


---
## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-11-23 at 17 31 33_e7d608b6](https://github.com/user-attachments/assets/4ec121bf-e5b5-4e2a-8bf8-b053fad533f4)


---
**D.INSTRUMENTATION AMPLIFIER**

THEORY:

An instrumentation amplifier is the intermediate stage of a instrumentation system. The signal source of the instrumentation amplifier is the output of the transducer. Many transducers output do not have the ability or sufficient strength to drive the next following stages. Therefore, instrumentation amplifiers are used to amplify the low-level output signal of the transducer so that it can drive the following stages such as indicator or displays.
The major requirements of a instrumentation amplifier are precise, low-level signal amplification where low-noise, low thermal and time drifts, high input resistance & accurate closed-loop gain, low power consumption, high CMRR & high slew rate for superior performance.
The output of Instumentation amplifier is given by
Vo = RF/R1[1+ 2R’/R][V2-V1]
 

## CIRCUIT DIAGRAM: INSTRUMENTATION AMPLIFIER

![WhatsApp Image 2025-11-23 at 17 47 12_61b9b5b1](https://github.com/user-attachments/assets/c28aa479-a4c0-418d-aa06-b3bb512c33b7)


PROCEDURE:

1.	Select the entire resistor with the same value. Let R be the gain varying resistor with different values of resistance for simplicity let R be a constant value.
2.	Connect the circuit as shown in the circuit diagram.
3.  + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
4.	Give the input V1 and V2 to the non-inverting terminals of first & second op-amp respectively.
5.	By varying the value of RG, measure the output voltage for common mode and differential mode operation. Since RG is selected as constant value, provide different input value of V1 and V2.
6.	Check the theoretical value with the experimental value.
7.	The output voltage is obtained in the Multimeter and the input and output voltage waveforms are plotted in a graph sheet

---

## TABULATION (Instrumentation Amplifier)

![WhatsApp Image 2025-11-23 at 17 47 12_8387e730](https://github.com/user-attachments/assets/3e65d9ae-a1a0-47c7-9411-b88cf47243d0)


---
## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-11-23 at 17 50 56_05cffc4e](https://github.com/user-attachments/assets/b3582168-1920-4247-8948-e9dee6c64a57)


---
## RESULT
Thus, the **Inverting**, **Non-Inverting**, **Differential**, and **Instrumentation Amplifiers** were designed and their performance successfully tested using Op-Amp IC 741.

---
