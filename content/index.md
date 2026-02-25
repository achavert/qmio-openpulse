---
title: Notebooks
layout: index
---

# Contents

These notebooks introduce the physical principles and pulse-level techniques used to control superconducting qubits on Qmio. They progressively move from the underlying physics of the qubit system to practical pulse implementations, spectroscopy techniques, and multi-qubit control. Along the way, we will connect the theoretical description of superconducting circuits with the OpenPulse framework, illustrating how low-level pulse programming can be used to study qubit dynamics, calibrate gates, and implement quantum operations directly at the hardware level.

## Notebooks

### [1. Introduction to qubit physics](notebook01.md)
To understand how quantum gates are implemented, we first need to examine the qubit's physical system. In this notebook, we will see how a qubit is encoded in superconducting circuits, which approximations can be used depending on our goals, what effects arise from the interactions with the thermal bath, how the qubit-resonator interaction enables measurements, and how to define the parameters of this systems in OpenPulse.

### [2. Single-qubit pulse control](notebook02.md)
The pulse-level implementation of some of the most common native gates will be explored, including the physical meaning of qubit driving, the different techniques and features available in Qmio using the OpenPulse grammar, and illustrative examples of gate calibration and single-qubit operations based on Rabi oscillations.

### [3. Qubit spectroscopy](notebook03.md)
Pulses give grain-level access to the transmon dynamics, like excitation to higher energy states. In this notebook we'll see how the qubit responds to pulses with different frequencies, exploring some observable fenomena at Qmio.


### [4. Two-qubit pulse control](notebook04.md)
Entanglement is one of the pillars behind quantum computing. On this notebook we will explore how the entanglement between qubit systems is physically achieved, which are the most common methods and how to implement some of them with OpenPulse.

## Documentation

### [OpenPulse grammar](notebookE1.md)

### [Pulse control theory notes](notebookE2.md)

---

# [Course materials](https://github.com/achavert/qmio-openpulse/blob/main/practices/)

This section provides access to the materials used in the in-person course, including the presentation (available in both web and PDF formats) and the hands-on exercises developed during the session. The repository also contains the completed versions of the exercises for reference.

## Slides
[Link to web version](https://www.canva.com/design/DAHBdmQNDFE/8PaGsgNXGk9oKSen7-YmTQ/edit?utm_content=DAHBdmQNDFE&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

[Link to pdf version](https://github.com/achavert/qmio-openpulse/blob/main/practices/Curso%20control%20por%20pulsos%20Qmio.pdf)

## Practices

### [Practice 1: Measuring T1](https://github.com/achavert/qmio-openpulse/blob/main/practices/practice1.ipynb)
Measure the energy relaxation time T1 of a qubit and analyze how the excited state population decays over time.

### [Practice 2: Pulse configuration](https://github.com/achavert/qmio-openpulse/blob/main/practices/practice2.ipynb)
Explore how control pulses are defined and configured to drive qubit dynamics at the pulse level.

### [Practice 3: X gate calibration](https://github.com/achavert/qmio-openpulse/blob/main/practices/practice3.ipynb)
Calibrate the X gate by tuning pulse parameters and analyzing the resulting qubit response.

### [Practice 4: Applying an RX(pi/4) with virtual RZ](https://github.com/achavert/qmio-openpulse/blob/main/practices/practice4.ipynb)
Implement an RX(pi/4) rotation using pulse-level control combined with virtual RZ frame updates.



