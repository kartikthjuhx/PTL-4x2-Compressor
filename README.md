# PTL-4x2-Compressor

This repository contains the designs, simulation results, and a research paper for an approximate 4:2 compressor and 4x4 multiplier, implemented using Pass-Transistor Logic (PTL) and simulated on Cadence Virtuoso using 180nm CMOS technology.

> **Note:** This research paper was not selected for publication but is shared here for educational and archival purposes.

---

## 📘 Project Overview

The project explores the design of low-power and high-speed 4:2 compressors using Pass-Transistor Logic (PTL), a technique that drastically reduces transistor count and improves efficiency. These compressors are then used in a 4x4 multiplier designed for error-tolerant applications like image processing, machine learning, and DSP.

Key highlights:
- Designed 3 variants of approximate 4:2 compressors.
- Used compressors in a 4x4 multiplier to analyze performance.
- Evaluated power, delay, and transistor count across designs.

---

## 🧠 Key Concepts

- **Approximate Computing:** Accepts small errors in output to improve power and speed efficiency.
- **4:2 Compressor:** Reduces 4 input bits (plus carry-in) into 2 output bits (sum and carry).
- **PTL (Pass-Transistor Logic):** Reduces transistor count by passing logic levels directly.

---

## ⚙️ Tools & Technology

- **Cadence Virtuoso**
- **180nm gpdk CMOS Technology**
- **Simulation environment for power, delay, and area analysis**

---

## 📊 Results Summary

| Design | Power (nW) | Delay (µs) | Transistors |
|--------|------------|------------|-------------|
| Design 1 | 840.56    | 3.71       | 26          |
| Design 2 | 843.91    | 3.99       | 22          |
| Design 3 | 550.82    | 2.89       | 18          |

- **Design 3** is the most efficient in terms of power and transistor count.

---

## 📄 Research Paper

You can read the full research paper here:  
📘 [`Kartik_JournalPaper.pdf`](research-paper/Kartik_JournalPaper.pdf)

---

## 🔍 Future Work

- Extending the compressor to larger multiplier sizes (e.g., 8x8, 16x16).
- Hardware implementation on FPGA or ASIC tape-out.
- Error-tolerant architecture for real-time DSP/ML use-cases.

---

## 🙏 Acknowledgements

Designed by **Kartik Thapa** under the guidance of **Dr. Menka Yadav**, during a summer internship at MNIT Jaipur.

---

## 📬 Contact

Feel free to reach out for collaboration or academic discussion:  
📧 kartik@example.com *(replace with your actual email)*
