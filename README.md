# Seismic Resilience Analysis of Water Distribution Systems
This repository contains a Jupyter notebook that focuses on the assessment of water distribution system serviceability following seismic events. The notebook employs the [**WNTR**](https://usepa.github.io/WNTR/) (Water Network Tool for Resilience) Python package to simulate hydraulic behavior and evaluate the impact of earthquakes on water infrastructure components including pipes, tanks, and pumps. Key features of the notebook include:

- Hydraulic simulation of the water distribution network to determine the system's response to seismic activity.
- Application of fragility curves to estimate the damage state of tanks and pumps based on peak ground acceleration (PGA) and to adjust their capacities accordingly.
- Calculation of serviceability metrics for different components of the water network, including the ratio of satisfied demand to required demand for junctions, the ratio of the water level post-earthquake to the original water level for tanks, and the operational capacity of pumps post-earthquake.

The case study focuses on the **Shelby County Water Distribution System**, with data sourced from the [**IN-CORE platform**](https://incore.ncsa.illinois.edu/).

The repository is intended for researchers, engineers, and practitioners interested in understanding and improving the resilience of water distribution systems in the face of natural disasters.

#### Getting Started
To use the code, clone the repository to your local machine.  
```git clone https://github.com/ZeinabFarah/WaterNet.git```

#### Contact
If you have any questions or comments about this repository, please contact farahmandfarzeinab@gmail.com.
