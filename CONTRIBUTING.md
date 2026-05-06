# Phase Kinetics: Rules of Engagement (CONTRIBUTING.md)

Thank you for your interest in the Phase Kinetics framework. 

This repository challenges fundamental parameters of the $\Lambda$ CDM standard model. Because the claims made here are highly disruptive, the standard for contributing to, altering, or challenging this codebase is uncompromisingly high. 

Please read these guidelines before submitting an Issue, participating in a Discussion, or opening a Pull Request.

## 1. The Core Philosophy: Math Over Philosophy
This is a mathematical and computational repository, not a philosophical battleground. 
* If you believe the continuous $SO(3,3)$ metric is incorrect, you must demonstrate the flaw mathematically.
* If you believe the van der Waals residual calculation is flawed, you must point to the specific error in the 36-state matrix or the 100-digit precision output.
* "Standard GR says otherwise" is not a valid counter-argument in this repository. You must attack the Phase Kinetics math directly.

## 2. Participating in Discussions
If you have questions about the theory, want to debate the topology, or need help understanding the derivations, please use the **Discussions** tab. Do not open an "Issue" for a theoretical debate. 

Maintain absolute professional rigor. Ad hominem attacks, condescension, or dismissive behavior will result in an immediate ban from the repository. Attack the math, respect the architect.

## 3. Submitting Code Changes (Pull Requests)
If you are submitting a refinement to the Python scripts, Mathematica notebooks, or mathematical documentation, follow this pipeline:

1. **Fork the Repository:** Create your own working copy.
2. **Maintain Precision:** The core Python verifier (`phase_kinetics.py`) relies on 100-digit arbitrary precision to bypass 64-bit float-collapse. Any code optimizations that compromise this precision or default to machine-level floating-point math will be instantly rejected.
3. **Test Your Build:** Before submitting, ensure your code compiles without warnings in standard Python 3.x or Mathematica. 
4. **Explain the "Why":** In your Pull Request description, explicitly state what anomaly your code fixes or what efficiency it introduces. 

## 4. The Adjudication Process
All Pull Requests are reviewed by the Lead Architect. Changes will only be merged if they mathematically strengthen the framework, correct a verified computational error, or significantly improve the visualization engines without violating the core topological constraints of the model.
