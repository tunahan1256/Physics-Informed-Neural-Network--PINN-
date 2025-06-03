# PARTICLE IN A BOX

Time independent Schrodinger equation of infinite square well is:
\begin{equation*}
\left[ \frac{-\hbar^2}{2m} \frac{\mathrm{d}^2 }{\mathrm{d}x^2} + V(x) \right] \psi = E\psi
\end{equation*}
Where:
\begin{equation*}
V(x) = \begin{cases} 
0 & \text{if } 0 \leq x \leq 1 \\
\infty & \text{otherwise}
\end{cases}
\end{equation*}

Analtytic solutions of this problem:
\begin{equation*}    
\psi_n(x) = \begin{cases} 
\sqrt{2} \sin(n\pi x) & \text{if } 0 \leq x \leq 1 \\
0 & \text{otherwise}
\end{cases}
\end{equation*}

\begin{equation*} 
    E_{n} = \frac{n^2 \pi^2}{2} 
\end{equation*}

Where, $\hbar$ and $m$ set to 1 and n represents the energy states

Jin, Henry, Marios Mattheakis, and Pavlos Protopapas. “Physics-Informed Neural Networks for Quantum Eigenvalue Problems.” arXiv.org, February 24, 2022. https://arxiv.org/abs/2203.00451. 

Jin, Henry, Marios Mattheakis, and Pavlos Protopapas. “Unsupervised Neural Networks for Quantum Eigenvalue Problems.” arXiv.org, October 10, 2020. https://arxiv.org/abs/2010.05075. 

Brevi, Lorenzo, Antonio Mandarino, and Enrico Prati. “A Tutorial on the Use of Physics-Informed Neural Networks to Compute the Spectrum of Quantum Systems.” arXiv.org, September 11, 2024. http://arxiv.org/abs/2407.20669v2. 

Moseley, Ben. “Harmonic-Oscillator-Pinn.” GitHub, 2021. https://github.com/benmoseley/harmonic-oscillator-pinn.
