# LTspice Simulation of a CMOS JK Flip-Flop

This document details the simulation and design of a JK Flip-Flop implemented using CMOS technology in LTspice.

## Overview

The JK Flip-Flop is a sequential logic circuit capable of storing a single bit of information. It improves upon the SR Flip-Flop by eliminating undefined conditions when both inputs are activated simultaneously. In this design, the circuit is implemented using complementary CMOS transistors.

## Functionality

The JK Flip-Flop operates according to the following logic:
- **J = 0, K = 0:** The output remains unchanged, preserving the stored state.
- **J = 1, K = 0:** The flip-flop is set, resulting in an output of 1.
- **J = 0, K = 1:** The flip-flop is reset, producing an output of 0.
- **J = 1, K = 1:** The output toggles, switching between the high and low states with each clock pulse.

## CMOS Technology Advantages

The use of CMOS (Complementary Metal-Oxide-Semiconductor) technology in this design offers several benefits:
- **Low Power Consumption:** CMOS circuits typically consume less power, making them suitable for modern electronic applications.
- **High Efficiency:** The complementary arrangement of NMOS and PMOS transistors provides efficient switching characteristics.
- **Robust Design:** CMOS technology ensures reliable performance and stability in digital circuits.

## LTspice Simulation

The circuit was modeled and simulated in LTspice, allowing for detailed analysis of its behavior under various input conditions. The simulation results validate the design, demonstrating correct functionality in accordance with the theoretical operation of a JK Flip-Flop. The dynamic response of the circuit, including set, reset, and toggle operations, was observed and confirmed.

## Contributors

- **Felipe Aparecido da Silva**  - [GitHub](https://github.com/gabipandrade)  
- **Gabriela Passos de Andrade**  - [GitHub](https://github.com/FehASilva)  
- **Rafael Cunha Bejes Learth** - [GitHub](https://github.com/RafaelLearth)  
- **Vitor Augusto Paiva de Brito**  - [GitHub](https://github.com/vtpaiva)  

## Conclusion

This LTspice simulation successfully demonstrates the operation of a CMOS-based JK Flip-Flop. The design not only meets the theoretical expectations but also highlights the efficiency and reliability of CMOS technology in digital circuit applications.

