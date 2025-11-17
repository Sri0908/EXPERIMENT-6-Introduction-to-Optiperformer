
Exp 6 Simulation of Optical Communication System
## Introduction to OptiPerformer 
## Objective
Download and install OptiPerformer software on your computer and run a sample file.

---

## Overview

Optiwave introduces **OptiPerformer**, a free photonic design automation tool that harnesses the full power of OptiSystem and creates specific dynamic design scenarios for student use.

In this exercise, you will:
- Download and install OptiPerformer on your PC/laptop.
- Use your license to load and run OptiSystem simulations prepared for this course.

The first simulation file (`Introduction_OptiPerformer.osp`) models a basic fiber optic system consisting of:
- A transmitter
- A fiber
- A receiver

The system includes:
- An optical power meter at the receiver input (fiber output)
- A Bit Error Rate (BER) analyzer

---

## Instructions

1. Download and install OptiPerformer from [optiwave.com](https://optiwave.com).  
2. Copy the `Introduction_OptiPerformer.osp` file to your PC.  
3. Launch OptiPerformer.  
4. Use the **File** menu or **Open File** button to open the fiber optic system file.  
5. Study the layout:
   - **Transmitter** section includes:
     - Binary source (PRBS generator)
     - Electrical pulse generator
     - Laser diode
     - External modulator  
   - **Receiver** section includes:
     - Photodiode
     - Low-pass filter
     - Decision circuit with BER analyzer  
6. Run the simulation using the **Start** button.  
   - Progress will be displayed.
   - Message “Calculation Finished!” appears upon completion.  
7. Double-click the **optical power meter** and **BER analyzer** windows.  
   - Check “Show Eye Diagram” in the BER window.  
   - Optical power meter shows power in watts and dBm.  
   - BER window displays:
     - Eye diagram
     - Max Q Factor
     - Min BER  
8. The simulation runs 5 iterations with fiber length varying from 50 to 150 km.  
   - Use forward/reverse buttons to step through iterations.  
   - Observe changes in received power, BER, Q factor, and eye diagram.

---

## Report

1. Cover sheet (as per attached example).  
2. Tabulation of received power, Q factor, and BER for 5 fiber lengths.  
3. Plot of received power, Q factor, and BER vs. fiber length.  
4. Description of eye diagram changes with increasing fiber length.

---

## Tabulation

**Transmission Analysis Across Fiber Lengths**

<img width="1280" height="899" alt="image" src="https://github.com/user-attachments/assets/41a712c7-4ed3-4545-90c9-2bb3845a47c9" />


## Graphs
### a) Simulation of Optical Communication System:
![exp6-1](https://github.com/user-attachments/assets/e8dd38fb-47e5-403b-9000-bcd0ec9198a4)

### b) Attenuation - limited fiber length:
![exp6-2](https://github.com/user-attachments/assets/eb99b27d-5e61-4abb-985e-0cb0f654e98d)
![exp6-2-1](https://github.com/user-attachments/assets/8b861696-0b05-4e35-adca-b94aa8778865)

### c)Dispersion limited fiber length:
<img width="824" height="1280" alt="image" src="https://github.com/user-attachments/assets/0da077eb-1bb0-49f3-9b8f-e9b73152e197" />

### d)Dispersion compensation:
<img width="810" height="1280" alt="image" src="https://github.com/user-attachments/assets/ddcab71b-8f06-43a9-adb6-00fc6e23891b" />
<img width="1600" height="1429" alt="image" src="https://github.com/user-attachments/assets/5cbc75c1-de2d-4e1e-b95a-c7c863f1da5c" />

### e)Gaussian pulse propagation:
<img width="861" height="1280" alt="image" src="https://github.com/user-attachments/assets/0d27d071-b0e2-4387-be55-c2eb6cd36b8f" />

### f)Receiver sensitivity:
<img width="1236" height="1600" alt="image" src="https://github.com/user-attachments/assets/8906546e-48e5-48ae-b0dc-18e3e714b439" />

## RESULT

The optical communication system was successfully simulated using OptiPerformer. As the fiber length increased from 50 km to 150 km, the following trends were observed:

Received optical power decreased due to fiber attenuation.
Q-factor gradually decreased, indicating signal quality degradation.
Bit Error Rate (BER) increased with distance, showing higher error probability.
The eye diagram became more closed at longer fiber lengths, confirming dispersion and noise effects.
Hence, the simulation verified that optical signal performance deteriorates with increasing fiber length due to attenuation and dispersion losses.
