## Learn Probability Density Functions using Roll-Number-Parameterized Non-Linear Model and GAN

This project transforms NO₂ concentration data using a roll-number-parameterized non-linear function and learns the unknown probability density function (PDF) using a Generative Adversarial Network (GAN).

---

## Methodology

- Load dataset and extract NO₂ feature (x).
- Compute roll-number-based parameters.
- Apply non-linear transformation to obtain z.
- Train GAN on transformed data.
- Generate samples from trained generator.
- Estimate PDF using Kernel Density Estimation (KDE).
- Plot learned PDF against real data distribution.

---


## Input

- NO₂ concentration values (x)
- Roll Number

---

## Output

- Transformed variable (z)
- Trained GAN model
- Generated samples from learned distribution
- Estimated probability density function (PDF)
- Comparison plot (Real distribution vs GAN-learned distribution)

---

