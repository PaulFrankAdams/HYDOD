# HYDODrive V2 – Audio-Amplifier Resonant Electrolyser

**Open Hydrogen Project • Humanitarian Release**

HYDODrive V2 builds upon the success of our original drycell driver system by exploring a historically verified variation: the use of **audio-frequency amplification** for water-splitting. Inspired by Dr. Henry Puharich’s patent [US3629521A], this version delivers resonant waveforms to a drycell electrolyser stack via a standard **low-impedance audio amplifier**, in place of digital gate-driven MOSFET arrays.

## 🎯 Purpose

To broaden the accessibility of resonant electrolysis systems for experimentation, prototyping, and humanitarian deployment — especially in low-tech or off-grid environments.

This approach uses:
- A **3-phase waveform generator** (RPi/Arduino/other SBC)
- A standard **audio amplifier** (e.g. 15 W/channel stereo amp)
- A **resonant drycell array** (CNANCNANCN…)
- Tuned LC tank circuit on the output line
- Optional signal shaping/filtering

By modulating and shaping the signal appropriately, the amplifier drives resonance in the water cell stack — *not dissimilar to acoustic excitation* — producing electrolysis at low current with improved efficiency.

---

## 🔧 Hardware Overview

| Component         | Description                                               |
|------------------|-----------------------------------------------------------|
| Waveform Source  | Pi HAT, Arduino Leonardo, Teensy, etc. (3-phase generator)|
| Amplifier        | Stereo or mono low-impedance audio amplifier              |
| Output Filtering | LC tank, snubber, flyback diode, phase tuning             |
| Drycell Stack    | CNANCNANCN… symmetric stainless steel drycell             |
| Optional         | Audio transformer for galvanic isolation                  |

---

## ⚠️ Variation Notice

> This design is a **humanitarian, open-source variation** of the original HYDODrive concept, built on public-domain principles as evidenced in US Patents including **US3629521A (Puharich)** and **US20050246059A1 (Meyer)**.

The addition of audio amplification as the signal delivery method shall be recognized as an *open derivative implementation*, not subject to patenting or restriction by any individual, group, or corporation. It is irrevocably released to the public domain under the following terms.

---

## 📜 Licensing and Disclosure

### License: [CERN-OHL-S v2](https://ohwr.org/cern_ohl_s_v2.txt) + Humanitarian Clause

This project and all variations are released under the **CERN Open Hardware License – Strongly Reciprocal v2**.  
In addition:

> ❗ **HUMANITARIAN ADDENDUM**  
> This project — including any amplifier-based variation — may **not be patented or sold under exclusive license**. It must remain **open, replicable, and free** for use in **research, education, and humanitarian applications**, especially those supporting **clean energy**, **safe water access**, or **climate-positive technologies**.

By contributing to this repository, you agree to maintain this principle of universal access and community benefit.

---

## 🧪 Current Status

- ✅ Initial audio-amplifier prototype tested at 15 V, 468 Hz
- ⚙️ Software generator under refinement (3-phase + sync pulse)
- 🔄 Additional testing underway with variable tank circuits
- 🔊 Acoustic resonance behavior under observation

---

## 🤝 Contribute

We welcome experimenters, engineers, and researchers of all backgrounds to fork, remix, and contribute.

---

## 🌍 Let It Flow

*Resonant water-splitting isn’t just efficient — it’s creating a new climate for a new world.*

**HYDODrive – Open Hydrogen Project**
