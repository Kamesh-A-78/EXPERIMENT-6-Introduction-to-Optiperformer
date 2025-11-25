
Exp 6 Simulation of Optical Communication System
## Introduction to OptiPerformer 
## Objective
Download and install OptiPerformer software on your computer and run a sample file.

---

## theory

Optiwave introduces OptiPerformer, a free photonic design automation tool which harnesses the full power of OptiSystem and creates specific dynamic design scenarios which can be used by students.
In this exercise, you will download and install OptiPerformer on your PC/laptop. Your license of OptiPerformer will be capable of loading and running OptiSystem simulations prepared for this course.
Once you have installed OptiPerformer, you can copy the first file (named: ‘Introduction_OptiPerformer.osp’) to your PC and run the simulation. The first file is a basic fiber optic system consisting of a transmitter, a fiber and a receiver. The system is “instrumented” with an optical power meter at the input to receiver (or the output of the fiber) and a bit error rate (BER) analyzer.



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
<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/e2a28469-89f7-400f-83b3-a470ac18a325" />

<img width="945" height="484" alt="image" src="https://github.com/user-attachments/assets/98b27190-88e4-41c7-b2d4-6e283238eaee" />

<img width="1123" height="387" alt="image" src="https://github.com/user-attachments/assets/2c52f5b2-9a90-41b0-85b4-33e5a452d7c3" />

## Tabulation

**Transmission Analysis Across Fiber Lengths**

| S.No | Fiber Length (km) | Optical Power (Watts) | Optical Power (dBm) | Max Q Factor | Min BER | Eye Height | Decision Instant (Max Q / Min BER) |
|------|-------------------|------------------------|----------------------|--------------|---------|-------------|-------------------------------------|
|      |                   |                        |                      |              |         |             |                                     |
|      |                   |                        |                      |              |         |             |                                     |
|      |                   |                        |                      |              |         |             |                                     |
|      |                   |                        |                      |              |         |             |                                     |
|      |                   |                        |                      |              |         |             |                                     |

---

## Graphs



## RESULT

*(Summarize key findings from simulation and analysis)*
