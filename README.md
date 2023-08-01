# Analysis_on_Hybrid_Ramjet


# Hybrid Ramjet Propulsion System Analysis

## Overview

The objective of this Colab notebook is to perform a chemical equilibrium analysis for a hybrid ramjet propulsion system. The analysis involves calculating various performance parameters, such as specific impulse (Isp), combustion temperature (Tc), and mass fraction (MF), for different oxidizer-to-fuel mixture ratios (MR) and chamber pressures (Pc). The analysis is conducted using the "rocketcea" library along with other Python libraries for data analysis and visualization.

## Installation

To run the analysis, you need to install the required libraries and packages. To install "rocketcea" for chemical equilibrium analysis, use the following command:

```
!pip install rocketcea
```

## How to Use

1. Import the necessary libraries:

```python
import numpy as np
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt
from rocketcea.cea_obj import CEA_Obj, add_new_fuel, add_new_oxidizer, add_new_propellant
```

2. Define the fuel and oxidizer cards, and get the "cea" output for a given mixture ratio and chamber pressure:

```python
# Define fuel and oxidizer cards
# ...
```

3. Perform analysis on combustion temperature, mass flow rate, and other parameters:

```python
# Analyze combustion temperature for a given mixture ratio
# ...
# Analyze mass flow rate of air for a given mixture ratio
# ...
# Analyze other parameters (e.g., Isp, Cstar, Tc, MolWt) for different O/F ratios
# ...
```

## Interactive Visualization

The notebook uses "matplotlib" and "seaborn" for static plots and "bokeh" for interactive data visualizations. The interactive plots allow users to hide/show specific lines by clicking on the legend items.

## Saving Results

The calculated results are saved to CSV files, enabling further analysis, data sharing, and presentation of the findings.

## Dependencies

The analysis depends on the following Python libraries:
- numpy
- pandas
- seaborn
- matplotlib
- rocketcea
- bokeh

## Contribution

If you find any issues or want to contribute to the analysis, feel free to create a pull request or open an issue.

## Acknowledgments

Special thanks to the authors of the "rocketcea" library for providing a powerful tool for chemical equilibrium analysis in propulsion systems.

## License

This Colab notebook is licensed under the gnu general public license v3.0.

## Disclaimer

This analysis is for educational and informational purposes only. The results may be used in comparison to the experimental results.

---

