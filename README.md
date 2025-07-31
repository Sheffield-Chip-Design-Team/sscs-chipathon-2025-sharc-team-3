# sscs-chipathon-2025-sharc-team-3

## 🔍 Project Goal

The goal of this project is to extend the OSU 3.3V 9-track standard cell library by designing and integrating two specialized sequential cells:  
- **Enable-controlled D Flip-Flop (DFFE)**  
- **Toggle Flip-Flop (TFF)**
  
These cells enhance the library’s capability for state retention, counters, and control logic.
------
## 🧠 High-Level Design

We propose to create two new standard cells (`DFFE_X1` and `TFF_X1`) as part of the GF180MCU_OSU_SC_GP9T3V3 library.  
The cells will be designed at 9-track height with 1X drive strength at 3.3V VDD.

The design and implementation flow involves:
- RTL Design
- SPICE-level simulation
- Layout using Magic
- Verification through test circuits such as a **stopwatch timer** using 7-segment display output

**------**

> 📷 **High Level Cell Specification and Logic Design**

<img width="479" height="218" alt="image" src="https://github.com/user-attachments/assets/df9a62f6-ec83-4dce-b0e7-566706d0738d" />

**------**

## 📅 Schedule

| Phase | Description |
|-------|-------------|
| **Phase 1** | OSU 3V39T standard cell research |
| **Phase 2a** | RTL Design and Layout |
| **Phase 2b** | Test Design Development |
| **Phase 3** | Library file generation using Synopsys tools |
| **Phase 4** | Characterization, comparison, and final checks before tapeout |

**------**

## 👥 Team Members

- **Swapnanil Chattopadhyay** (Team Lead)  
  fossi: `@swapnanil:matrix.org`  
- **James Ashie Kotey** – IC Engineering Intern at EnSilica (specializing in SV Verification with UVM)  
- **K Arjunan** – Software Development Intern at P&G  

We are ECE students at the University of Sheffield with experience in RTL-to-GDS using OpenLane and are contributors to the ongoing TinyTapeout project.
**------**

## 📹 Video Links

- [SSCS Proposal Video](https://drive.google.com/file/d/1Xd0uH8zoMggjvoABHvagSLX6_qmq6p1x/view?usp=sharing)  

**------**

## 🔗 References

- [Enable Flip-Flops Blog Post](https://asicdigitaldesign.wordpress.com/2008/10/27/fun-with-enable-flip-flops/)  
- [T Flip-Flop - GeeksforGeeks](https://www.geeksforgeeks.org/digital-logic/t-flip-flop/)  
- [GlobalFoundries PDK GitHub](https://github.com/stineje/globalfoundries-pdk-libs-gf180mcu_osu_sc)

**------**
