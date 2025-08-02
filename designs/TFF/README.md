# T Flip-Flop (TFF) – Xschem Design

This folder contains the Xschem schematic for a T Flip-Flop (TFF) circuit. The TFF is a type of flip-flop that toggles its output on each clock pulse when the T (toggle) input is high.

## ⚙️ Description

- **Inputs**:  
  - `T`: Toggle input  
  - `CLK`: Clock signal  
- **Output**:  
  - `Q`: Output state  
  - `Q̅`: Inverted output 

The TFF toggles its output `Q` on the rising (or falling) edge of the clock signal if `T=1`. If `T=0`, the output retains its previous state.

## 🛠️ Tools Used

- **Xschem**: For schematic capture  
- **Ngspice**: For simulation

© 2025 | SHARC Chipathon Team 3
