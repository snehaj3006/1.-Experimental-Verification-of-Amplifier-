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
<img width="305" height="162" alt="image" src="https://github.com/user-attachments/assets/2e44efa1-69c5-4462-8421-89017bdc2868" />

CIRCUIT DIAGRAM: INVERTING AMPLIFIER:

<img width="262" height="157" alt="image" src="https://github.com/user-attachments/assets/740133d6-d02b-48d3-857a-432708ede077" />

MODEL GRAPH 

<img width="237" height="225" alt="image" src="https://github.com/user-attachments/assets/dfb917e5-58fa-4e05-ab5e-240af4336211" />



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

<img width="384" height="218" alt="image" src="https://github.com/user-attachments/assets/fda530ba-605f-422c-94bd-3e25d3690376" />



---
## OUT PUT WAVEFORM AND DISCUSSION 
<img width="433" height="645" alt="image" src="https://github.com/user-attachments/assets/dcc0d28d-3bba-4b5c-aa36-3b694f36bfbd" />

![WhatsApp Image 2025-11-17 at 21 19 42_9a0b82d2](https://github.com/user-attachments/assets/dfd5901b-7e2b-48b7-a9ea-de06020e0d7b)

---
### **Non-Inverting Amplifier**

If the signal is applied to the non-inverting input terminal without inversion, it is called a **non-inverting amplifier**.  
Here, the output is fed back to the inverting terminal, and **no phase shift** occurs.


ACL = 1 + RF/R1


---

## CIRCUIT DIAGRAM
<img width="245" height="243" alt="image" src="https://github.com/user-attachments/assets/3d8d060c-4730-4398-b2b7-29e90d6847d5" />


## MODEL GRAPH
<img width="303" height="211" alt="image" src="https://github.com/user-attachments/assets/c338dbbe-f5c0-4810-bc81-882de2c5f14b" />


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
<img width="409" height="206" alt="image" src="https://github.com/user-attachments/assets/8055b915-d4a7-4592-8cee-52c70f7555e2" />


## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-11-17 at 21 19 42_ca23a5d0](https://github.com/user-attachments/assets/81b7ff64-9c33-4abb-8525-712d180deef6)

![WhatsApp Image 2025-11-17 at 21 19 43_4623bace](https://github.com/user-attachments/assets/a80e80ad-38ee-4d54-a7a0-3e6f59c1c39c)

---
## DIFFERENTIAL AMPLIFIER

A circuit that amplifies the **difference** between two input signals is called a **Differential Amplifier**.  
It is useful in instrumentation applications.  
If the two input signals are identical, the output is ideally **zero**.


A = Vo/{V2 - V1} = -Rf/R1
## CIRCUIT DIAGRAM
<img width="304" height="232" alt="image" src="https://github.com/user-attachments/assets/06ae99ea-57a2-45c7-aac6-9e1432a814e2" />

MODEL GRAPH1:



## DESIGN


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

<img width="394" height="234" alt="image" src="https://github.com/user-attachments/assets/394955d0-bd26-4e51-8638-b2999b9511e9" />


---
## OUT PUT WAVEFORM AND DISCUSSION 

![WhatsApp Image 2025-11-17 at 21 19 43_a8d225a0](https://github.com/user-attachments/assets/4002adeb-c7da-49a8-a9dc-3b406e51ceb5)


## INSTRUMENTATION AMPLIFIER

THEORY:

An instrumentation amplifier is the intermediate stage of a instrumentation system. The signal source of the instrumentation amplifier is the output of the transducer. Many transducers output do not have the ability or sufficient strength to drive the next following stages. Therefore, instrumentation amplifiers are used to amplify the low-level output signal of the transducer so that it can drive the following stages such as indicator or displays.
The major requirements of a instrumentation amplifier are precise, low-level signal amplification where low-noise, low thermal and time drifts, high input resistance & accurate closed-loop gain, low power consumption, high CMRR & high slew rate for superior performance.
The output of Instumentation amplifier is given by
Vo = RF/R1[1+ 2R’/R][V2-V1]
 

## CIRCUIT DIAGRAM: INSTRUMENTATION AMPLIFIER

<img width="1006" height="1087" alt="image" src="https://github.com/user-attachments/assets/636c08f9-7940-470e-a89e-4891d57a9ac7" />

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

![WhatsApp Image 2025-11-17 at 21 24 11_f1fd9266](https://github.com/user-attachments/assets/16ecf88e-00c1-4f40-98ad-2348b68a9005)

---
## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-11-17 at 21 24 43_6c15e3d7](https://github.com/user-attachments/assets/1cb93433-e601-4152-9659-6bcb1a49b974)


---
## RESULT
Thus, the **Inverting**, **Non-Inverting**, **Differential**, and **Instrumentation Amplifiers** were designed and their performance successfully tested using Op-Amp IC 741.

---
