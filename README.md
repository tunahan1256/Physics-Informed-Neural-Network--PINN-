# PARTICLE IN A BOX

The time-independent Schrödinger equation for an infinite square well is:

$$
\left[ \frac{-\hbar^2}{2m} \frac{\mathrm{d}^2 }{\mathrm{d}x^2} + V(x) \right] \psi = E\psi
$$

Where the potential is defined as:

$$
V(x) = \begin{cases} 
0 & \text{if } 0 \leq x \leq 1 \\
\infty & \text{otherwise}
\end{cases}
$$

### Analytic Solutions

The wavefunctions are given by:

$$
\psi_n(x) = \begin{cases} 
\sqrt{2} \sin(n\pi x) & \text{if } 0 \leq x \leq 1 \\
0 & \text{otherwise}
\end{cases}
$$

The corresponding energy levels are:

$$
E_n = \frac{n^2 \pi^2}{2}
$$

Where \( $\hbar$ \) and \( m \) are set to 1, and \( n \) represents the quantum energy states.

---

### References

- Jin, Henry, Marios Mattheakis, and Pavlos Protopapas. “Physics-Informed Neural Networks for Quantum Eigenvalue Problems.” *arXiv.org*, February 24, 2022. [arXiv:2203.00451](https://arxiv.org/abs/2203.00451)

- Jin, Henry, Marios Mattheakis, and Pavlos Protopapas. “Unsupervised Neural Networks for Quantum Eigenvalue Problems.” *arXiv.org*, October 10, 2020. [arXiv:2010.05075](https://arxiv.org/abs/2010.05075)

- Brevi, Lorenzo, Antonio Mandarino, and Enrico Prati. “A Tutorial on the Use of Physics-Informed Neural Networks to Compute the Spectrum of Quantum Systems.” *arXiv.org*, September 11, 2024. [arXiv:2407.20669v2](http://arxiv.org/abs/2407.20669v2)

- Moseley, Ben. “Harmonic-Oscillator-Pinn.” *GitHub*, 2021. [GitHub Repository](https://github.com/benmoseley/harmonic-oscillator-pinn)
