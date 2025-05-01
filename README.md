
---

# CMOS-Based 16-Bit Magnitude Comparator  
**Birzeit University – Electrical and Computer Engineering Department**  

---

## 📄 Project Overview

This project presents the **design, implementation, and simulation** of a **low-power, high-speed CMOS 16-bit magnitude comparator**. The development follows a hierarchical design approach—starting from a 1-bit comparator, scaling to 4-bit, and finally building a 16-bit comparator. The circuit operates on a supply voltage of **0.8V** to balance **power efficiency and speed**, making it suitable for modern digital applications such as arithmetic units, signal processors, and data sorting systems.

---

## 🔧 Design Process

### ➤ 1-Bit Comparator
- Built using **basic CMOS gates**: NOR, XNOR, AND, OR, and inverters.
- Provides 2 outputs: **A = B**, **A > B**.
- Designed with minimal transistor delay and compact layout.

### ➤ 4-Bit Comparator
- Composed of **four 1-bit comparators** and higher-input AND/OR gates.
- Implements hierarchical logic to determine bitwise dominance.
- Outputs: **A = B**, **A > B**.

### ➤ 16-Bit Comparator
- Constructed from **four 4-bit comparators** and supporting logic gates.
- Provides **three outputs**: **A > B**, **A < B**, **A = B**.
- NOR gate included to handle less-than condition.

---

## 📐 CMOS Layout and Schematic

The design includes both **schematic-level logic** and **custom transistor-level layouts** for:
- 1-bit comparator
- 4-bit comparator
- 16-bit comparator

Each layout was carefully optimized to maintain symmetry, minimize parasitic capacitance, and reduce overall silicon area.

---

## 🧪 Simulation Results

Simulations were conducted at **0.8V supply**:

### ✔ 1-Bit Comparator
- Outputs responded correctly to input changes with negligible delay.
- Demonstrated **functional accuracy** and **low-power behavior**.

### ✔ 4-Bit Comparator
- Correctly identified equal and greater-than conditions.
- Outputs transitioned in sync with input changes.

### ✔ 16-Bit Comparator
- Validated complete functional behavior for all output conditions.
- Minor glitches observed due to **propagation delay mismatches**, but outputs stabilized quickly.
- Demonstrated overall **speed, accuracy, and power efficiency**.

---


## 🎯 Key Achievements

- Hierarchical comparator design from 1-bit to 16-bit.
- Optimized for **low voltage operation (0.8V)**.
- Validated through accurate **layout vs. schematic (LVS)** and **DRC**-clean layouts.
- Successfully **met timing and power targets** for digital integration.

---

## ✍️ Authors 

**Yara Khattab**  

  📧 [yarakhattab16@gmail.com](mailto:yarakhattab16@gmail.com) 

  
  🔗 [GitHub: @yarakhattab](https://github.com/yarakhattab)

**Shahd Shreteh**  
  🎓 Computer Engineering Student – Birzeit University  
  

**Ahmad Elyyan**  
  🎓 Computer Engineering Student – Birzeit University  

