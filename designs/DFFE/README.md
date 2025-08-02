# D Flip-Flop with Enable – Xschem Design

This folder contains the Xschem schematic for a **D Flip-Flop (DFF) with Enable** control. The circuit stores the input value `D` on the output `Q` when the Enable signal is active. The output remains unchanged when Enable is low.

## ⚙️ Description

- **Inputs**:  
  - `D`: Data input  
  - `Enable`: Control signal (acts like a clock gate)  

- **Outputs**:  
  - `Q`: Stored output  
  - `Q̅`: Inverted output  

When `Enable` is high, the value on the `D` input is latched and propagated to the output `Q` through the internal SR latch. When `Enable` is low, the outputs remain stable, regardless of changes on `D`.

The circuit uses basic logic gates:
- Inverter  
- AND gates to generate Set (`S`) and Reset (`R`) signals  
- NOR-based SR latch for output storage

## 🛠️ Tools Used

- **Xschem**: For schematic capture  
- **Ngspice**: For simulation 

---

© 2025 | SHARC Chipathon Team 3
