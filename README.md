# Principal Component Analysis (PCA) for Temperature and Humidity
Overview
This repository contains a Jupyter Notebook (PCA.ipynb) analyzing the influence of temperature on relative humidity using Principal Component Analysis (PCA). The project was conducted by Oduro Yeboah Joshua, Mensah Charles, and Dzahene Richmond K. Elorm.
Objective
To apply PCA to quantify how temperature affects relative humidity by identifying patterns and variance in the data.
Methodology

Standardize Data: Center temperature and humidity by subtracting their means.
Compute Variance/Covariance: Calculate variances and covariance for the covariance matrix.
Eigenvalues/Eigenvectors: Derive principal components (PCs) from the covariance matrix.
Visualize: Generate scatter plot, scree plot, and PCA biplot.

Results

Scatter Plot: No clear linear relationship between standardized temperature and humidity.
Scree Plot: PC1 (humidity-driven) explains 80% of variance; PC2 (temperature-driven) explains 20%.
PCA Biplot: Humidity strongly loads on PC1, temperature on PC2.

Conclusions

No clear linear relationship between temperature and humidity.
Humidity dominates variance (80% via PC1), with temperature contributing less (20% via PC2).

Recommendations

Include multi-season or multi-year data for broader analysis.
Add meteorological factors (e.g., wind speed, pressure) to assess their impact.
Combine PCA with regression to quantify temperature's effect on humidity.




References

Hecht et al. (2024). Journal of Chemical Physics, 161(22), 224904.
Dyer, I. (2012). Measurement: Journal of the International Measurement Confederation.
Britannica. (2025). Encyclopaedia Britannica.
Abdi & Williams. (2010). Wiley Interdisciplinary Reviews: Computational Statistics, 2(4), 433–459
