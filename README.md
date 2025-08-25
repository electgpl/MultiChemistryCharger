# CN3765 Multi-Chemistry Charger

This project implements a **multi-chemistry battery charger** based on the **CN3765** monolithic IC.  
The CN3765 is a high-efficiency step-down (buck) controller that supports **Li-Ion, LiFePO₄, and Lead-Acid (SLA)** batteries, providing accurate constant-current (CC) and constant-voltage (CV) charging profiles.  

The entire hardware design was developed from scratch, including schematic, PCB layout, and component selection, ensuring a stable and reliable charger suitable for embedded systems and lab use.  

---

## 🔑 Features

- Based on **CN3765 monolithic multi-chemistry charger IC**.  
- High-efficiency **buck (step-down) topology**.  
- Supports multiple battery chemistries:  
  - **Li-Ion (4.2 V/cell)**  
  - **LiFePO₄ (3.65 V/cell)**  
  - **Lead-Acid (SLA)**  
- Accurate **CC/CV charging algorithm**.  
- Charge termination by tail current detection.  
- Typical input range: **5 V – 28 V** (depending on application).  
- Integrated protections:  
  - Overcurrent protection  
  - Thermal shutdown  
  - Fault condition handling  
- **2-layer PCB**, optimized for thermal dissipation and low EMI.  

---

## 📂 Repository structure

- **/schematic/** → Circuit schematic files.  
- **/pcb/** → PCB layout files ready for fabrication.  
- **/doc/** → Technical notes and application information.  
- **/img/** → Rendered PCB images and assembled prototype pictures.  

---

## 🔧 Typical applications

- Portable power systems.  
- Battery banks for IoT nodes.  
- Lab prototypes with different battery chemistries.  
- Low-power solar charging systems with storage.  

---

## 📑 References

- [CN3765 Datasheet (Consonance)](http://www.consonance-elec.com/pdf/datasheet/DSE-CN3765.pdf)  
- [CN3765 Application Notes](http://www.consonance-elec.com/download.asp)  

---

## 📸 Project preview

*(Insert here a PCB render and/or assembled prototype photo for quick reference)*  

---

## ⚖️ License

This project is released under the **MIT License**.  
You are free to use, modify, and distribute it, provided that proper credit is given.  

---
