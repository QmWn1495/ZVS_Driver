# ZVS Driver

## What
This is a ZVS(Zero Voltage Switching) Mazzalli circuit

## Why
A Zero Voltage Switching driver is usually made to efficiently drive high frequency power electronics. In this case, it will be used to drive a High Voltage AC Transformer, which will be used to drive a CW(Cockcroft-Walton) Voltage Multiplier.

## Schematic

<img width="872" height="340" alt="image" src="https://github.com/user-attachments/assets/2a83265e-f71e-484d-8746-918076a8d1b3" />


Full schematic, contains Input(J1, F1, C3, C4), Feed Choke(L1; rated 13.5A at 47uH), Switches(Q1, Q2; both IRFP250N), Gate Driving and Protection(R1, R2, R3, R4, D1, D2, D3, D4), and the Resonant tank(J1, C1, C2; C1||C2)

## PCB

<img width="461" height="354" alt="image" src="https://github.com/user-attachments/assets/58840101-d9bd-48a5-9a5b-fdd1db125904" />

2-layer board, 68mm x 55.8mm, all components on top side. All the traces were routed on F.Cu in order to allow for a solid GND pour on B.Cu. 2oz copper is needed for this board to operate at full rating(10A, meaning ~14A peak). The drain nets keep a minimum 0.8mm clearance to account for the ~94V peak.

## 3D Model

<img width="593" height="458" alt="image" src="https://github.com/user-attachments/assets/6ad8b5ed-4851-4c86-9506-91d6f79a7bb9" />

(From KiCad's 3D Viewer)



