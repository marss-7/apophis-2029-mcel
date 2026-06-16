# Orbital Dynamics Analysis: (99942) Apophis Close Encounter (2029)

This repository contains a detailed study and numerical simulation of the Near-Earth Asteroid (99942) Apophis, focusing on its predicted close encounter in the year 2029. The project examines the problem from multiple physical perspectives to validate the trajectory and understand the gravitational perturbations affecting the body.

## Project Description

The project is structured around three fundamental approaches to celestial mechanics:

1. **N-Body Integration:** Implementation of a 16-body simulation to calculate the real trajectory of Apophis, integrating gravitational forces from major Solar System bodies to determine the minimum encounter distance to Earth.
2. **Keplerian Propagation:** Use of osculating orbital elements and numerical solution of Kepler's Equation to validate the trajectory via an idealized elliptical approximation, serving as an analytical baseline.
3. **Circular Restricted Three-Body Problem (CRTBP):** Analysis of the effective potential topology in the rotating (synodic) Sun-Earth frame. This model allows for the visualization of the energy landscape, identification of forbidden regions (zero-velocity curves), and understanding of system stability through the Jacobi Constant.

## Note on Performance and Execution

> **Important regarding Notebook execution:**
> Due to memory management and the internal state of the Jupyter kernel, running all cells simultaneously ("Run All") may cause the notebook controller to be disposed. For optimal results and to avoid kernel errors, **it is recommended to run the cells sequentially**, allowing each block to complete its process before starting the next.

## Transparency and Authorship Notes

* **GitHub Visualization:** All output cells have been cleared before uploading the repository. This was done specifically to ensure that graphs and results are rendered correctly in the GitHub interface, avoiding rendering errors for large `.ipynb` files.

* **Code Development:** All code contained in this repository was written by the author (Marhia José Granada Restrepo). GitHub Copilot's code completion was used as a technical assistance tool, but the logic, implementation, and validation are original.

* **Documentation and Theory:** The explanatory texts and theoretical foundation of this project were drafted through a collaborative process with Gemini. The physical theory and concepts were provided by the author, and Gemini assisted in the drafting and technical structuring of the content to ensure clarity and academic precision. The author has personally reviewed, edited, and adjusted each section to ensure the tone and information accurately reflect the work performed.