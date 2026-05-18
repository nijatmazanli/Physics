```
███╗   ██╗██╗     ██╗ █████╗ ████████╗    ███╗   ███╗ █████╗ ███████╗ █████╗ ███╗   ██╗██╗     ██╗
████╗  ██║██║     ██║██╔══██╗╚══██╔══╝    ████╗ ████║██╔══██╗╚════██║██╔══██╗████╗  ██║██║     ██║
██╔██╗ ██║██║     ██║███████║   ██║       ██╔████╔██║███████║   ██ ╔╝███████║██╔██╗ ██║██║     ██║
██║╚██╗██║██║██   ██║██╔══██║   ██║       ██║╚██╔╝██║██╔══██║ ██ ╔╝  ██╔══██║██║╚██╗██║██║     ██║
██║ ╚████║██║╚█████╔╝██║  ██║   ██║       ██║ ╚═╝ ██║██║  ██║███████║██║  ██║██║ ╚████║███████╗██║
╚═╝  ╚═══╝╚═╝ ╚════╝ ╚═╝  ╚═╝   ╚═╝       ╚═╝     ╚═╝╚═╝  ╚═╝        ╚═╝  ╚═╝╚═╝  ╚═══╝╚══════╝╚═╝
```

### Physics Guide Series — Electronics & Circuit Theory

**Nijat Mazanli** — Baku, Azerbaijan · 2026

[![Verified](https://img.shields.io/badge/Verified%20by-Telman%20Askeraliyev-c8f060?style=flat-square&labelColor=0e0e1a)](https://www.linkedin.com/in/physics-teacher-azerbaijan-telman-askeraliyev/)
[![Academia](https://img.shields.io/badge/Academia.edu-Published-60d4f0?style=flat-square&labelColor=0e0e1a)](https://independent.academia.edu/NijatMazanl%C4%B1)
[![SlideShare](https://img.shields.io/badge/SlideShare-Published-f0b060?style=flat-square&labelColor=0e0e1a)](https://www.slideshare.net/nicatmazanli)
[![YouTube](https://img.shields.io/badge/YouTube-Channel-f06060?style=flat-square&labelColor=0e0e1a)](https://www.youtube.com/@nicatmazanli)
[![Tinkercad](https://img.shields.io/badge/Tinkercad-Simulations-e060c0?style=flat-square&labelColor=0e0e1a)](https://www.tinkercad.com)

---

> Visual guides, lab reports, and engineering projects on electronics —
> created by a student from Baku, verified by Physics Teacher Telman Askeraliyev.

| | |
|---|---|
| **Author** | Nijat Mazanli |
| **Co-Author** | Najabat Sophiyeva |
| **Verified by** | Telman Askeraliyev — Fizika Müəllimi, Baku |
| **LinkedIn** | https://www.linkedin.com/in/physics-teacher-azerbaijan-telman-askeraliyev/ |
| **Instagram** | https://www.instagram.com/physics_teacher_azerbaijan |
| **Year** | 2026 |
| **Type** | Visual Guides · Lab Reports · Engineering Projects · Market Research |
| **Location** | Azerbaijan, Baku |

---

## 📋 Contents

- [01 — Field Effect Transistors](#01--field-effect-transistors-fet)
- [02 — Amplifiers & Applications](#02--amplifiers--applications)
- [03 — Transistor Lab Report](#03--transistor--technical-lab-report)
- [04 — Capacitor Guide](#04--capacitor--visual-guide)
- [05 — Voltage Divider](#05--voltage-divider--physics-guide)
- [06 — Azerbaijan Electronics Market](#06--azerbaijan-electronics-market--analysis)
- [Author](#-author)
- [Find Me](#-find-me)

---

## 01 — Field Effect Transistors (FET)

> Comprehensive visual guide — JFET, E-MOSFET, D-MOSFET, operating regions, key formulas.

**Links:**

- 📄 [Academia.edu](https://www.academia.edu/165906555)
- 📊 [SlideShare](https://www.slideshare.net/slideshow/physics-guide-field-effect-transistors-nijat-mazanli-najabat-sophiyeva-verified-by-physics-teacher-azerbaijan-telman-askeraliyev-fizika-muellimi-azerbaijan-baku/287120657)

**Verified by:** Telman Askeraliyev — Physics Teacher, Azerbaijan, Baku
🔗 https://www.linkedin.com/in/physics-teacher-azerbaijan-telman-askeraliyev/

### Guide Overview

| # | Section | Key Content |
|---|---|---|
| 01 | What is a FET? | Voltage-controlled device, Gate/Drain/Source terminals, amplification & switching |
| 02 | JFET | PN junction gate, Shockley equation, depletion region, self-bias |
| 03 | Operating Regions | Ohmic (switch), Saturation (amplifier), Cutoff (OFF state) |
| 04 | MOSFET | E-MOSFET vs D-MOSFET, SiO₂ insulated gate, threshold voltage |
| 05 | Device Comparison | JFET vs E-MOSFET vs D-MOSFET — 6 properties side-by-side |
| 06 | Applications | Signal gain, high-impedance buffer, switching, VCR |

### Key Formulas

| Formula | Description |
|---|---|
| `I_D = I_DSS × (1 − V_GS / V_P)²` | Shockley equation — JFET drain current (saturation) |
| `I_D = k(V_GS − V_T)²` | E-MOSFET saturation drain current |
| `rDS(on) = V_DS / I_D` | On-resistance (Ohmic region) |
| `V_GS = −I_D × R_S` | JFET self-bias |
| `A = V_out / V_in` | Voltage gain |

### Device Comparison

| Property | JFET | E-MOSFET | D-MOSFET |
|---|---|---|---|
| Gate Insulation | PN junction (reverse-biased) | SiO₂ oxide layer | SiO₂ oxide layer |
| Input Impedance | ~10⁷ Ω (very high) | ~10¹⁴ Ω (extremely high) | ~10¹⁴ Ω (extremely high) |
| Channel at V_GS = 0 | ✓ ON — exists | ✗ OFF — no channel | ✓ ON — exists |
| Zero Bias Possible? | No | No | Yes — V_GS=0 → I_D=I_DSS |
| VGS Range (N-ch) | 0 to V_P (negative) | Positive (must be > V_T) | Positive or negative |
| Main Application | Low-noise analog amplifiers | Digital circuits, power switching | Analog amplifiers |

### JFET Operating Regions

| Region | Condition | Use Case |
|---|---|---|
| Ohmic | V_DS < V_GS − V_P | Voltage-variable resistor (switch) |
| Saturation | V_DS ≥ V_GS − V_P | Amplification, constant current source |
| Cutoff | V_GS ≤ V_P | FET fully OFF — I_D ≈ 0 |

**Subject:** Electronics / Semiconductor Devices · Visual Guide · English · Azerbaijan, Baku

---

## 02 — Amplifiers & Applications

> Lesson presentation — amplifier types, gain, frequency response, real-world applications.

**Links:**

- 📄 [Academia.edu](https://www.academia.edu/165709848)
- 📊 [SlideShare](https://www.slideshare.net/slideshow/physics-guide-amplifiers-and-applications-lesson-presentation-and-practical-insights-nijat-mazanlli-najabat-sophiyeva-verified-by-physics-teacher-azerbaijan-telman-askeraliyev-fizika-muellimi-azerbaijan-baku/287037260)

**Verified by:** Telman Askeraliyev — Physics Teacher, Azerbaijan, Baku
🔗 https://www.linkedin.com/in/physics-teacher-azerbaijan-telman-askeraliyev/

### Topics Covered

| # | Section | Content |
|---|---|---|
| 01 | Introduction | Definition, voltage/current/power gain, classifications |
| 02 | Amplifier Types | Common-emitter, common-base, common-collector configurations |
| 03 | Gain & Formulas | A = Vout/Vin, Ap = Pout/Pin, dB calculations |
| 04 | Frequency Response | Bandwidth, cutoff frequencies, Bode plot basics |
| 05 | Applications | Audio, RF, and instrumentation amplifiers |

### Key Formulas

| Formula | Description |
|---|---|
| `A_V = V_out / V_in` | Voltage gain |
| `A_P = P_out / P_in` | Power gain |
| `A_dB = 20 × log₁₀(A_V)` | Voltage gain in decibels |
| `BW = f_H − f_L` | Bandwidth |

**Subject:** Electronics / Analog Circuits · Educational Presentation · English · Azerbaijan, Baku

---

## 03 — Transistor — Technical Lab Report

> Hands-on lab report with circuit diagrams, measurements, characteristic curves, Q-point analysis.

**Links:**

- 📊 [SlideShare](https://www.slideshare.net/slideshow/technical-laboratory-report-transistor-report-nijat-mazanli-najabat-sofiyeva-verified-by-physics-teacher-azerbaijan-telman-askeraliyev-fizika-muellimi-azerbaijan-baku/286914601)

**Verified by:** Telman Askeraliyev — Physics Teacher, Azerbaijan, Baku
🔗 https://www.linkedin.com/in/physics-teacher-azerbaijan-telman-askeraliyev/

### Report Overview

| # | Section | Content |
|---|---|---|
| 01 | Introduction | Transistor types, BJT vs FET, circuit symbols |
| 02 | Circuit Diagram | Schematic, component list, measurement setup |
| 03 | Measurements | Collector current, base current, hFE (β) calculations |
| 04 | Characteristic Curves | I_C vs V_CE output characteristics |
| 05 | Analysis | Operating point (Q-point), load line, saturation/cutoff |
| 06 | Conclusion | Key findings, sources of error, recommendations |

### Key Parameters

| Parameter | Symbol | Significance |
|---|---|---|
| Current gain | hFE / β | Ratio of collector to base current |
| Collector current | I_C | Output current |
| Base current | I_B | Control current |
| Operating point | Q-point | DC bias condition on load line |
| Saturation voltage | V_CE(sat) | Minimum V_CE when transistor is fully ON |

**Subject:** Electronics / Semiconductor Devices · Technical Lab Report · English · Azerbaijan, Baku

---

## 04 — Capacitor — Visual Guide

> Capacitor theory, types, charging/discharging, RC time constant, practical applications.

**Links:**

- 📊 [SlideShare](https://www.slideshare.net/slideshow/capacitor-najabat-sofiyeva-and-nijat-mazanli-verified-by-physics-teacher-azerbaijan-telman-askeraliyev-fizika-muellimi-azerbaijan-baku/286799493)

**Verified by:** Telman Askeraliyev — Physics Teacher, Azerbaijan, Baku
🔗 https://www.linkedin.com/in/physics-teacher-azerbaijan-telman-askeraliyev/

### Key Formulas

| Formula | Description |
|---|---|
| `C = Q / V` | Capacitance definition |
| `τ = R × C` | RC time constant |
| `E = ½ × C × V²` | Energy stored in capacitor |
| `1/C_total = 1/C1 + 1/C2` | Capacitors in series |
| `C_total = C1 + C2` | Capacitors in parallel |

### Topics Covered

1. **What is a Capacitor?** — Charge storage, electric field, dielectric
2. **Types of Capacitors** — Ceramic, electrolytic, film, variable
3. **Charging & Discharging** — RC time constant τ = RC, exponential curves
4. **Applications** — Filtering, energy storage, timing circuits, coupling/decoupling

**Subject:** Electronics / Passive Components · Visual Guide · English · Azerbaijan, Baku

---

## 05 — Voltage Divider — Physics Guide

> Theory, mathematical derivation, loading effects, transistor biasing, sensor signal scaling.

**Links:**

- 📊 [SlideShare](https://www.slideshare.net/slideshow/physics-guide-voltage-divider-nijat-mazanli-najabat-sophiyeva-verified-by-physics-teacher-azerbaijan-telman-askeraliyev-fizika-muellimi-azerbaijan-baku/287278278)

**Verified by:** Telman Askeraliyev — Physics Teacher, Azerbaijan, Baku
🔗 https://www.linkedin.com/in/physics-teacher-azerbaijan-telman-askeraliyev/

### Key Formulas

| Formula | Description |
|---|---|
| `V_out = V_in × R2 / (R1 + R2)` | Voltage divider output |
| `k = R2 / (R1 + R2)` | Divider ratio |
| `I = V_in / (R1 + R2)` | Series current |
| `R2_eff = R2 × RL / (R2 + RL)` | Loaded output (with R_L) |

### Applications

| Application | Use Case |
|---|---|
| Logic Level Shifting | 5V → 3.3V for ESP32 / STM32 |
| ADC Sensor Scaling | 0–12V sensor → 0–5V Arduino input |
| Transistor Base Biasing | Setting BJT Q-point via VCC divider |
| Potentiometer | Variable voltage control |
| LDR Light Sensor | `V_out = V_S × R / (R + R_LDR)` — threshold switching |

**Subject:** Electronics / Circuit Theory · Visual Guide · English · Azerbaijan, Baku

---

## 06 — Azerbaijan Electronics Market — Analysis

> Sales trends, component availability, pricing dynamics, and strategic insights for the local market.

**Links:**

- 📊 [SlideShare](https://www.slideshare.net/slideshow/physics-guide-an-analysis-of-azerbaijan-s-electronics-market-focusing-on-sales-authors-necabet-sofiyeva-nicat-mazanli-verified-by-physics-teacher-azerbaijan-telman-askeraliyev-fizika-muellimi-azerbaijan-baku/287388776)

**Verified by:** Telman Askeraliyev — Physics Teacher, Azerbaijan, Baku
🔗 https://www.linkedin.com/in/physics-teacher-azerbaijan-telman-askeraliyev/

### Report Overview

| # | Section | Content |
|---|---|---|
| 01 | Market Overview | Azerbaijan electronics sector size, growth trends |
| 02 | Sales Analysis | Component categories, demand patterns, key suppliers |
| 03 | Pricing Dynamics | Import costs, local vs. international pricing comparison |
| 04 | Opportunities | Growth areas for students, engineers, and entrepreneurs |
| 05 | Conclusions | Key takeaways and strategic recommendations |

**Subject:** Market Research / Economics of Technology · Analysis · English · Azerbaijan, Baku

---

## 👤 Author

| | Nijat Mazanli |
|---|---|
| **Role** | Author · Engineer |
| **Co-Author** | Najabat Sophiyeva |
| **Location** | Baku, Azerbaijan |
| **Skills** | Electronics · Circuit Theory · Physics · Education |

---

## ✅ Verified by Physics Teacher

All guides reviewed and certified by **Telman Askeraliyev** — Fizika Müəllimi, Baku, Azerbaijan.

| Platform | Link |
|---|---|
| LinkedIn | https://www.linkedin.com/in/physics-teacher-azerbaijan-telman-askeraliyev/ |
| Instagram | https://www.instagram.com/physics_teacher_azerbaijan |

---

## 🔗 Find Me

| Platform | Link |
|---|---|
| Academia.edu | https://independent.academia.edu/NijatMazanl%C4%B1 |
| LinkedIn | https://www.linkedin.com/in/nicatmazanli/ |
| YouTube | https://www.youtube.com/@nicatmazanli |
| SlideShare | https://www.slideshare.net/nicatmazanli |

---

*Physics Guide Series · 2026 · Baku, Azerbaijan*
