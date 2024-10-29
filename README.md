# Calibration and Evaluation of Sunshine-Based Empirical Models for Estimating Daily Solar Radiation in Northern Ghana

Accurate estimation of solar radiation is essential for optimizing solar energy applications, agricultural practices and environmental management, particularly in regions with limited measured data. This project focuses on the calibration and evaluation of sunshine-based empirical models to estimate daily solar radiation in the northern region of Ghana.

## Objectives

- **Calibration**: To calibrate empirical models (e.g., Angström–Prescott model) to suit local climate conditions in northern Ghana.
- **Evaluation**: To evaluate the performance of these models using statistical metrics like MBE, RMSE, and correlation coefficients.
- **Validation**: To validate the model against measured solar radiation data and optimize for better accuracy.

## Data Sources

The project uses the following data:
- **Sunshine Duration**: Measured or satellite-derived sunshine duration (hours).
- **Solar Radiation**: Measured or reanalysis-based solar radiation data (e.g., from NASA POWER or ERA5 datasets).

## Empirical Models

We use the following empirical models to estimate solar radiation:
- **Angström–Prescott Model**:
  \[
  H = H_0 \left(a + b \cdot \frac{S}{S_0}\right)
  \]
  Where:
  - \( H \) is the daily solar radiation,
  - \( S \) is the measured sunshine duration,
  - \( H_0 \) and \( S_0 \) are the extraterrestrial radiation and maximum possible sunshine duration, respectively,
  - \( a \) and \( b \) are empirical coefficients.

Other models such as the **Hargreaves-Samani** model may also be explored.

## Calibration and Evaluation

- **Calibration**: The models are calibrated using sunshine duration data from 1991 to 2020 in the northern region of Ghana.
- **Evaluation**: Performance metrics used for evaluation include:
  - **Mean Bias Error (MBE)**,
  - **Root Mean Square Error (RMSE)**,
  - **Coefficient of Determination (R²)**.
  
## Results

The project demonstrates that calibrated sunshine-based models can effectively estimate daily solar radiation in regions with limited measurement stations. The best-performing model is applied to optimize solar energy utilization and agricultural management practices in northern Ghana.



