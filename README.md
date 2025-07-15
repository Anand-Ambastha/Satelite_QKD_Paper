
# Satellite QKD Constellation Simulation and Evaluation

This repository contains datasets, figures, and simulation results supporting the paper:

**"Design and Comparative Evaluation of Satellite Constellation Architectures for Quantum Key Distribution over Indian Ground Stations"**

...

## Overview

This work evaluates multiple Low Earth Orbit (LEO) satellite constellation configurations for Quantum Key Distribution (QKD) across selected Indian ground stations. Using a synthetic Walker constellation and realistic TLE modeling, we quantify:

- Secure Key Rate (SKR)
- Quantum Bit Error Rate (QBER)
- Pass elevation profiles
- Ground station performance comparison

...

## Repository Contents

### Figures
- `QBERvsSKER.png`: Scatter plot showing Average QBER vs Total SKR per ground station.
- `elevation_[GroundStation].png`: Elevation vs Time plots.

### Datasets
- `qkd_results_[GroundStation].csv`: Computed metrics per pass.
- `synthetic_tle_list.txt`: TLE file.

...

## Ground Stations Evaluated
- Hanle
- Dehradun
- Mt. Abu
- Shillong
- Kodaikanal

...

## How to Reproduce Figures

Example code:

```python
import matplotlib.pyplot as plt
plt.figure(figsize=(6,4))
plt.plot(qber, skr, 'o-')
plt.xlabel("Average QBER")
plt.ylabel("Total SKR (bits/pass)")
plt.title("QBER vs Total SKR per Ground Station")
plt.savefig("QBERvsSKER.tiff", dpi=1200)
````

...

## Citation

```
[Anand K. , Yugunanda M. , Aayush G.]. "Design and Simulation of a Decoy-State BB84 Satellite QKD Constellation for Indian Ground Stations".
```

...

## Contact

* Author: Anand Kumar
* LinkedIn: \[[Anand Kumar](https://www.linkedin.com/in/anand-kumar05)]
* GitHub: \[[Anand Kumar](https://github.com/Anand-Ambastha)]
* Email: \[[verma05anand@gmail.com](mailto:verma05anand@gmail.com)]

...

## License

Academic use only.

```
