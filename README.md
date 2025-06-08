# 🧠 Quantum Image Negation using Cirq

A quantum take on a classic image processing task—**image negation**. This project demonstrates how to simulate image negation using **quantum gates** with the help of **Cirq**, Google's quantum computing framework.

---

## 📌 Problem Statement

In classical image processing, image negation involves flipping pixel values:  
- `0 ➝ 1`  
- `1 ➝ 0`  

This project replicates that logic using **quantum NOT gates (X gates)** on **qubits** that represent image pixels.

---

## ✅ Project Goals

- Simulate quantum logic on binary (black & white) images using Cirq.
- Encode each pixel as a qubit.
- Apply an X gate to invert each qubit's state.
- Measure the qubits to retrieve the negated values.
- Reconstruct and display the final (negated) image.
- Compare quantum negation to classical negation.

---

## 🛠 Tools & Libraries

- 🧪 [Cirq](https://quantumai.google/cirq) – Quantum circuit simulation  
- 📊 NumPy – Matrix and array operations  
- 🖼️ Pillow (PIL) – Image loading and manipulation  
- 📺 IPython.display – Inline image rendering in notebooks  

---

## 🧪 How It Works

1. Load a **black & white image**.
2. For each pixel:
   - Convert `0` or `1` to a qubit state |0⟩ or |1⟩.
   - Apply an X (NOT) gate to flip the qubit.
   - Measure the qubit to obtain the new pixel value.
3. Reassemble the negated image from measured results.
4. Display original vs. quantum-negated image.

---
![Untitled design (3)](https://github.com/user-attachments/assets/65863413-0fef-4349-a1e2-938fe19ce26a)
