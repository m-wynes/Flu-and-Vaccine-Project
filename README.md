# Impact of Influenza Vaccination Coverage on Influenza Burden in the United States

### Objective
The objective of this project was to explore the relationship between state-level influenza vaccination coverage and state-level reported influenza case counts across three different influenza seasons.

### Data
* **Source**: The Centers for Disease Control and Prevention (CDC)
* **Timeframe**: 2022-2023, 2023-2024, & 2024-2025 influenza seasons
* **Scale**: U.S. State-level lab-confirmed influenza cases and vaccination coverage data

### Methods
* Data cleaning and standardization using R
* Exploratory data analysis and visualization
* Statistical analyses including:
  * Summary statistics
  * Pearson's correlation coefficient
  * Multiple linear regression modeling
  * Welch's two-sample t-tests
  * Season-specific regression analyses

### Key Findings
The statistical analyses revealed that state-level vaccination coverage showed an inconsistent relationship with reported influenza case counts across the three examined seasons. Some seasons suggested that a higher vaccination rate corresponded to fewer reported influenza cases, while other seasons suggested the opposite. These inconsistencies are likely due to confounding factors, such as population size, variations in testing volume, and differences in surveillance intensity amongst the 50 states. These findings showcase the complexity of interpreting real-world public health data, and emphasize the need for context-specific analysis for each flu season.

### Public Health Context
Overall, this project demonstrates how real-world evidence (RWE) and public health surveillance workflows are commonly used to evaluate population-level health interventions. The project also demonstrates how statistical modeling, data analysis, and careful data interpretation are required when working with observational healthcare data to avoid drawing misleading conclusions.

### Tools
R, dplyr, janitor, ggplot2
