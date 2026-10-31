# Gas Well Liquid Loading Analysis

A Python-based gas-well production surveillance tool that applies **Turner’s critical-velocity correlation** to assess liquid-loading risk and identify potential production constraints as gas rates decline.

## Project Overview

Liquid loading occurs when gas velocity becomes insufficient to carry liquid droplets to the surface, causing liquid accumulation in the wellbore and potentially reducing gas-well productivity.

This project models gas-well production trends, calculates actual and critical gas velocities, and compares actual production rates against critical rates to screen for potential liquid-loading conditions.

## Objectives

- Estimate in-situ gas density, volumetric flow rate, and gas velocity.
- Calculate critical gas velocity using Turner’s correlation.
- Compare actual gas velocity with critical velocity to assess liquid-loading risk.
- Track changes in gas production and critical flow-rate thresholds.
- Visualize production performance through a multi-panel diagnostic dashboard.

## Technologies Used

- **Language:** Python
- **Environment:** Google Colab
- **Libraries:** NumPy, Pandas, Matplotlib
- **Engineering Model:** Turner critical-velocity correlation


## How to Run

1. Open Google Colab.
2. Create a new Python notebook.
3. Copy the project code into a notebook cell.
4. Run the cell to generate synthetic production data, calculate diagnostic parameters, and display the dashboard.

### Dependencies

```bash
pip install numpy pandas matplotlib
```

## Key Engineering Applications

- Gas-well production surveillance
- Preliminary liquid-loading risk screening
- Critical gas-rate assessment
- Evaluation of declining gas-well deliverability
- Identification of wells that may warrant further deliquification assessment

## Limitations

- The analysis uses synthetic data rather than field measurements.
- Turner’s correlation provides an estimate of the critical liquid-carrying velocity; it does not directly confirm liquid loading.
- The screening thresholds are illustrative and should be calibrated against field conditions and operating experience.
- The model does not simulate transient multiphase flow, pressure-drop behavior, or the performance of specific deliquification methods.

Consequently, the output should be treated as a preliminary engineering screening tool, not a substitute for field validation or detailed well-performance analysis.

## Future Improvements

- Integrate real production data from CSV files.
- Add configurable tubing geometry and fluid properties.
- Incorporate production-history trend analysis and configurable alert thresholds.
- Extend the workflow to evaluate potential deliquification options.

## Author

**Vishakha Khatri**  
B.Tech, Petroleum Engineering  
IIT (ISM) Dhanbad
