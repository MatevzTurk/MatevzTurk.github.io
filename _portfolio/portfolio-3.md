---
title: "Investigating Thermodynamics of Simple Water Models"
excerpt: "Investigation of the phase behavior and anomalous properties of core-softened water models using molecular simulations and integral equation theory.<br/><img src='/images/Urbic.png'>"
collection: portfolio
---

When setting up molecular simulations, one of the main considerations is computational cost. Simulating large systems—especially biomolecular systems in aqueous solution, such as proteins—quickly becomes expensive because treating all water molecules explicitly requires significant computational resources. To address this, simplified water models have been developed that reproduce essential features of water while greatly reducing simulation cost.

Before a water model can be used reliably, its thermodynamic and structural properties must be characterized to ensure that it captures the key behaviours of real water. This project focuses on studying a family of simplified water models known as core-softened models, in which each water molecule is represented as a point-like particle interacting through an isotropic pair potential featuring two characteristic interaction length scales.

Our goal is to investigate whether these models can reproduce hallmark properties of water, including its thermodynamic anomalies and phase behaviour. To do this, we combine tools from statistical mechanics, employing both molecular simulations (Monte Carlo and molecular dynamics in various ensembles) and integral equation theory to analyze the behaviour of these models across a range of conditions.

---

<br/>

<img src="/images/Urbic.png" alt="Example of a core-softened potential" width="500"/>

*Figure: Four types of ice appearing in a core-softened CSW model in 2 dimensions under various thermodynamic conditions.*

---

**Publications:**
- [Turk, M.; Tomaz Urbic. Areas of Anomalous Properties as Function of Shape of Potential. Fluid Phase Equilibria 2024, 577, 113988–113988.](https://www.sciencedirect.com/science/article/pii/S0378381223002686)
- [Turk, M.; Tomaz Urbic. Integral Equation Theory Study of the Two Dimensional SRSS Model. Computational and Theoretical Chemistry 2024, 115036–115036.](https://www.sciencedirect.com/science/article/pii/S2210271X24005759)

---

For the full simulation software (MC/MD codes for 2D systems), see the GitHub repository **[here](https://github.com/MatevzTurk/MS_Software)**.
