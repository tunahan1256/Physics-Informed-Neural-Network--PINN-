# 🧠🔬 Physics-Informed Neural Networks (PINN) for Solving the Schrödinger Equation

This repository implements a Physics-Informed Neural Network (PINN) to solve the **time-independent Schrödinger equation** for a **quantum particle in an infinite potential well**. By incorporating the physical laws into the loss function, the model predicts the wave function and energy levels of the quantum system with minimal data requirements.

---

## 📌 Objectives

- ✅ Solve the Schrödinger equation using Physics-Informed Neural Networks (PINNs).
- ✅ Estimate quantum **energy levels (E)** using a neural network-based approach.
- ✅ Compare the **PINN-predicted solutions** with **analytical solutions** (wavefunctions and energy levels).

---

## 📐 Problem Definition

We consider a particle in an infinite square well where the potential is defined as:

$$
V(x) = \begin{cases}
0 & \text{if } 0 \leq x \leq 1 \\
\infty & \text{otherwise}
\end{cases}
$$

The Schrödinger equation becomes:

$$
\left[ \frac{-\hbar^2}{2m} \frac{d^2}{dx^2} + V(x) \right] \psi(x) = E \psi(x)
$$

With boundary conditions:
- $\( \psi(0) = \psi(1) = 0 \)$
- $\( \hbar = m = 1 \)$ for simplicity

---

## ⚙️ General Structure of the Implementation

- ✅ Selection of an **activation function**
- ✅ Construction of a **neural network**
- ✅ Definition of **required derivative functions** using automatic differentiation
- ✅ Construction of **model layers**
- ✅ Implementation of the **physics-informed loss function**, including the Schrödinger residual
- ✅ **Training** to minimize the combined boundary and physics loss
- ✅ **Comparison** of PINN outputs with the analytical wavefunctions and energy levels

---

## 📊 Results

The model successfully estimates:
- The ground and excited state **wave functions**
- Corresponding **energy eigenvalues**
  
These are compared with the analytical solutions:
- $\( \psi_n(x) = \sqrt{2} \sin(n \pi x) \)$
- $\( E_n = \frac{n^2 \pi^2}{2} \)$

---

## 🧠 References

- Jin, H., Mattheakis, M., & Protopapas, P. (2022). [Physics-Informed Neural Networks for Quantum Eigenvalue Problems](https://arxiv.org/abs/2203.00451)
- Jin, H., Mattheakis, M., & Protopapas, P. (2020). [Unsupervised Neural Networks for Quantum Eigenvalue Problems](https://arxiv.org/abs/2010.05075)
- Brevi, L., Mandarino, A., & Prati, E. (2024). [A Tutorial on PINNs to Compute the Spectrum of Quantum Systems](http://arxiv.org/abs/2407.20669v2)
