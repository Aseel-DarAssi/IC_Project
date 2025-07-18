# Design of Low Power N×N Magnitude Comparator Using GDI Technique

This project presents the **design, implementation, and simulation of a low-power N×N-bit magnitude comparator** using the **Gate Diffusion Input (GDI)** technique. The comparator was tested for 1-bit, 2-bit, 4-bit, and 8-bit configurations, and the results demonstrate **significant improvements in power consumption, delay, and area** compared to conventional CMOS-based designs.

---

## Abstract

The project focuses on designing high-speed, low-power digital circuits using the **GDI technique**. GDI provides a reduced transistor count and improved efficiency. Simulation results show that the **GDI-based 8-bit comparator** consumes only **77.0162 µW** and has a delay of **1.27205 ns**, compared to **114.3 µW** and **29.75 ns** for the CMOS version, respectively.

---

## Comparator Configurations

The design was implemented hierarchically:

| Bit-width | Constructed Using         |
|-----------|---------------------------|
| 1-bit     | From scratch using GDI    |
| 2-bit     | Two 1-bit comparators     |
| 4-bit     | Two 2-bit comparators     |
| 8-bit     | Two 4-bit comparators     |

Each comparator produces three outputs: **A > B**, **A = B**, and **A < B**.

---

## Technology & Tools

- **Technology Node**: 300nm
- **NMOS Width**: 4μm  
- **PMOS Width**: 8μm  
- **Length (both)**: 2μm
- **Tool Used**: ELECTRIC EDA Tool v9.07
  
---

## References

1. [IRJET Paper on GDI Comparators](https://www.irjet.net/archives/V6/i7/IRJET-V6I7509.pdf)  
2. [JETIR Paper](https://www.jetir.org/papers/JETIR1903917.pdf)  
3. [Academia.edu Paper – Design in 45nm/90nm](https://www.academia.edu/25840062/...)  
4. [Semantic Scholar – 2-bit GDI Comparator](https://www.semanticscholar.org/paper/...)  
5. [Another Academia.edu Paper](https://www.academia.edu/44351018/...)
