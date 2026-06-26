# Evolutionary Dynamics: Wright-Fisher Simulation

This project provides an interactive simulation of population genetics using the **Wright-Fisher model**. It allows users to observe how three fundamental evolutionary forces—**Genetic Drift**, **Natural Selection**, and **Mutation**—shape allele frequencies over time.

## Overview

Built in **Python** and hosted on **Google Colab**, this tool bridges the gap between static biological data (like phylogenetic trees) and dynamic evolutionary modeling. By adjusting parameters via an interactive interface, users can simulate population behavior and visualize the "mutation-selection-drift balance."

## Core Concepts

The simulation models the following evolutionary dynamics:

* **Genetic Drift:** Stochastic fluctuations in allele frequency due to random sampling, which is especially impactful in small populations.
* **Natural Selection:** The directional trend caused by differential fitness, where favorable alleles increase in frequency over time.
* **Mutation:** The introduction of new genetic variation, which prevents the permanent fixation or loss of alleles.

## Features

* **Interactive Controls:** Use sliders to adjust population size ($N$), fitness coefficients, mutation rates, and the number of simulation replicates.
* **Dynamic Visualization:** Real-time plotting of allele frequencies, allowing for the observation of stochastic "wiggles" (drift) and directional selection trends.
* **Reproducibility:** Designed for scientific transparency, allowing users to toggle parameters to explore mutation-selection balance.

## Installation & Usage

1. **Clone the repository:**
```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git

```


2. **Run:** Open `notebooks/simulation.ipynb` in Google Colab.
3. **Dependencies:** Ensure `numpy`, `matplotlib`, and `ipywidgets` are installed in your environment.

