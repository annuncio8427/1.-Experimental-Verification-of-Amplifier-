#**EX.NO:** 1  # EXPERIMENTAL VERIFICATION OF AMPLIFIER INVERTING, NON INVERTING , DIFFERENTIAL AMPLIFIER AND INSTRUMENTATION AMPLIFIERS
**DATE:**  
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
| 6 | Resistors | 1K, 10K, 2.2K | 2 |
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

### **Inverting Amplifier**

This is the most widely used op-amp configuration.  
The output voltage Vo  is fed back to the inverting input terminal through the  Rf - R1 network.  
The negative sign in gain indicates a **phase shift of 180°**.


Acl = -RF/R1

PIN DIAGRAM
![WhatsApp Image 2025-11-28 at 1 33 22 PM](https://github.com/user-attachments/assets/183cf71e-1459-4adc-b0ba-959f4f77d806)


CIRCUIT DIAGRAM: INVERTING AMPLIFIER:
![WhatsApp Image 2025-11-28 at 11 32 38 AM](https://github.com/user-attachments/assets/a12f4a78-8bf5-4e9a-bd68-92f75bb68df2)


MODEL GRAPH 
![WhatsApp Image 2025-11-28 at 1 02 48 PM](https://github.com/user-attachments/assets/8854df68-9e0c-4445-b285-723000b4869a)


DESIGN:

Inverting amplifier:

A = -Rf/R1
Take  A = 10
Rf =10 R1
Choose R1 = 1kΩ, Rf=10kΩ

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

![WhatsApp Image 2025-11-28 at 11 32 39 AM](https://github.com/user-attachments/assets/bff33dce-bafb-4a6c-8a93-d44108f71545)

 


---
## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-11-28 at 1 07 22 PM](https://github.com/user-attachments/assets/379dd952-cffe-4443-88d3-b252159cf238)


---
### **Non-Inverting Amplifier**

If the signal is applied to the non-inverting input terminal without inversion, it is called a **non-inverting amplifier**.  
Here, the output is fed back to the inverting terminal, and **no phase shift** occurs.


ACL = 1 + RF/R1


---

## CIRCUIT DIAGRAM

![WhatsApp Image 2025-11-28 at 1 11 06 PM](https://github.com/user-attachments/assets/4ac5a2e1-743a-4ae2-8346-927706bfe9c0)

---

## MODEL GRAPH
![WhatsApp Image 2025-11-28 at 1 12 43 PM](https://github.com/user-attachments/assets/cae1bc0b-5203-4820-9a8c-c88f95b988a4)


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
![WhatsApp Image 2025-11-28 at 1 13 50 PM](https://github.com/user-attachments/assets/33e5d479-e889-43f9-91e2-29923bd82abd)


---
## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-11-28 at 1 15 02 PM](https://github.com/user-attachments/assets/08af14cd-87f2-4661-b721-00d1c59aea18)


---
## DIFFERENTIAL AMPLIFIER

A circuit that amplifies the **difference** between two input signals is called a **Differential Amplifier**.  
It is useful in instrumentation applications.  
If the two input signals are identical, the output is ideally **zero**.


A = Vo/{V2 - V1} = -Rf/R1
## CIRCUIT DIAGRAM
![WhatsApp Image 2025-11-28 at 1 18 55 PM](https://github.com/user-attachments/assets/08e93410-697f-4a05-909c-b2b9d5cb7974)



## MODEL GRAPH
![WhatsApp Image 2025-11-28 at 1 24 29 PM](https://github.com/user-attachments/assets/e10144bf-2d55-4ac4-a0b9-5d0d54208862)


---

## DESIGN
![WhatsApp Image 2025-11-28 at 1 26 48 PM](https://github.com/user-attachments/assets/248eceb4-f3b4-4402-bb47-b571f9079428)



### **Differential Amplifier**

AV = Vo/{V1 - V2} = -Rf/R1


Take  A = 10 
⇒  Rf = 10R1   
Choose  R1 = 1kOhm, Rf = 10kOhm

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

![WhatsApp Image 2025-11-28 at 1 19 19 PM](https://github.com/user-attachments/assets/c09d09ae-4e1c-4014-aee7-314684f4968d)


---
## OUT PUT WAVEFORM AND DISCUSSION 
==
![WhatsApp Image 2025-11-28 at 1 22 59 PM](https://github.com/user-attachments/assets/31fa6f46-d263-4e97-9c78-8e8c5627604a)

---
## INSTRUMENTATION AMPLIFIER

THEORY:

An instrumentation amplifier is the intermediate stage of a instrumentation system. The signal source of the instrumentation amplifier is the output of the transducer. Many transducers output do not have the ability or sufficient strength to drive the next following stages. Therefore, instrumentation amplifiers are used to amplify the low-level output signal of the transducer so that it can drive the following stages such as indicator or displays.
The major requirements of a instrumentation amplifier are precise, low-level signal amplification where low-noise, low thermal and time drifts, high input resistance & accurate closed-loop gain, low power consumption, high CMRR & high slew rate for superior performance.
The output of Instumentation amplifier is given by
Vo = RF/R1[1+ 2R’/R][V2-V1]
 

## CIRCUIT DIAGRAM: INSTRUMENTATION AMPLIFIER



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
![WhatsApp Image 2025-11-28 at 1 30 31 PM](https://github.com/user-attachments/assets/bd234630-6864-4f76-9ef9-88eac7c5c5af)


---
## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-11-28 at 1 31 36 PM](https://github.com/user-attachments/assets/d9bb9803-5cb1-493c-8f19-ee18942ab681)

![WhatsApp Image 2025-11-28 at 1 32 18 PM](https://github.com/user-attachments/assets/8fa3e338-b08f-4378-b749-0a029d041eb8)

---
## RESULT
Thus, the **Inverting**, **Non-Inverting**, **Differential**, and **Instrumentation Amplifiers** were designed and their performance successfully tested using Op-Amp IC 741.

---
