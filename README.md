# Interturn-Short-Diagnosis-in-Transformers-Central-Signal-Injection-Approach
Designed and implemented a central signal injection-based method to detect inter-turn faults in transformer wind ings



## 🔍 Overview

This project investigates a novel method to diagnose **inter-turn faults in transformer windings** using a **Central Signal Injection (CSI)** approach. The diagnosis is conducted by injecting different types of impulse signals and analyzing the **frequency response** of the transformer.

We utilize **Lightning Impulse Frequency Response Analysis (LIFRA)** and **Switching Impulse Frequency Response Analysis (SIFRA)** to study how signal waveshape affects diagnostic accuracy. The goal is to identify faults **without dismantling the transformer**, making this technique practical and non-intrusive.

---

## 🎯 Objectives

- Design and implement a **central signal injection system** for fault diagnosis in transformers.
- Analyze the impact of **impulse waveshape** on frequency response analysis.
- Identify **location and severity** of faults using transfer function characteristics.
- Validate the approach using **experimental data** from a test transformer.

---

## ⚙️ Methodology

1. **Test Setup**:  
   - A low-voltage transformer was used for experimentation.  
   - Inter-turn faults were introduced at controlled levels for analysis.

2. **Signal Injection**:  
   - Two types of impulse signals were used:
     - **Lightning Impulse (LI)**
     - **Switching Impulse (SI)**
   - Signals were injected into the **central node** of the winding under test.

3. **Data Collection**:  
   - Voltage responses from various terminals were recorded.  
   - The transfer function was derived using **FFT analysis**.

4. **Analysis**:  
   - Comparison between healthy and faulty states was done.  
   - Frequency domain characteristics were extracted and plotted.  
   - Special attention was paid to **low- and mid-frequency bands**, where fault indicators are most prominent.

---

## 🔬 Key Findings

- **Waveshape** significantly affects the diagnostic performance — LI and SI yield different sensitivity profiles.
- The **central signal injection** approach enhances fault localization by isolating the impact to a focused region.
- **Interturn faults** cause observable changes in the **frequency response**, especially in mid and low-frequency regions.
- The method enables **non-destructive testing** of transformers, avoiding the need for dismantling.

---


---

## 🛠 Tools & Technologies

- Oscilloscope (for signal measurement)
- Low-voltage test transformer

---

## 👨‍🔬 Team Members

- **Shanmugapriya**
- **Lingareddy Sai Sruthi**
- **A. Sri Sarvesh**

**Guide**: Dr. S. Natarajan  
**Department**: School of Electrical and Electronics Engineering, SASTRA Deemed University

---

## 📈 Future Scope

- Extend analysis to **high-voltage transformers**.
- Automate fault detection using **Machine Learning models**.
- Explore **multi-point injection** for deeper insight into winding behavior.

---

## 📜 Citation

If you use this work for academic or research purposes, please cite:
> Shanmugapriya, L.S. Sruthi, A.S. Sarvesh, "Interturn Short Diagnosis in Transformers: Central Signal Injection Approach", SASTRA SEEE, 2025.

---

## 📬 Contact

For queries or collaboration, reach out to:  
📧 [126005041@sastra.ac.in]  
📍 SEEE, SASTRA University, Tamil Nadu, India

---



