# Pressure-Dependent Vibrational Energy Relaxation of HF in Acetonitrile

## 🔬 Overview

Vibrational energy relaxation (**VER**) governs how excess vibrational energy is redistributed from an excited molecule to its surroundings and plays an important role in chemical dynamics, energy transport, and reaction processes in condensed phases.

While VER has been extensively studied under ambient conditions, its behavior under high pressure remains much less understood, particularly when compression alters local packing, intermolecular interactions, and phase structure.

In this project, we use **machine-learning-accelerated molecular dynamics** to investigate the pressure-dependent VER of vibrationally excited **HF in acetonitrile (CH₃CN)** across **liquid, amorphous, and crystalline states**.

## 🧪 Simulation Systems

We investigate vibrationally excited **HF in acetonitrile (CH₃CN)** across four thermodynamic states spanning ambient to high-pressure conditions. These systems were selected to probe how **compression, local molecular packing, and long-range structural order** influence vibrational energy relaxation.

| Pressure | Phase / State | Description |
|---|---|---|
| **1 bar** | Liquid | Low-density disordered liquid under ambient conditions |
| **5 kbar** | Amorphous | Intermediate-pressure disordered state with increased molecular packing |
| **20 kbar** | High-density amorphous (HDA) | Densely packed amorphous solid |
| **20 kbar** | Crystalline | High-density ordered crystalline solid |

The comparison across these states allows us to examine the evolution of VER with increasing pressure and to assess the roles of **density**, **local packing**, and **structural order** through cross-comparison of liquid, amorphous, and crystalline environments.

> [!NOTE]
> The two systems at **20 kbar** provide a direct comparison between amorphous and crystalline environments at the same pressure, enabling the influence of long-range structural order to be examined separately from the overall effect of compression.

## 🤖 Machine-Learning Potential

> [!IMPORTANT]
> The machine-learning potential provided in this repository was developed for the HF/CH₃CN system and validated for the thermodynamic states investigated in this work. Its transferability to other compositions, temperatures, or pressure ranges has not been established.

## ⚙️ Simulation Workflow

> [!WARNING]
> VER simulations require extensive nonequilibrium trajectory sampling to obtain converged relaxation dynamics. GPU acceleration is recommended for production calculations.

## 📊 Analysis

...

## ▶️ Usage

...

## 📚 Citation

...
