# Impact of Influenza Vaccination Coverage on Influenza Burden in the United States

### Objective
To assess the relationship between state-level influenza vaccination coverage and reported influenza case counts across multiple U.S. influenza seasons using CDC surveillance data.

### Data
* **Source**: Centers for Diseas Control and Prevention (CDC)
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
Across three influenza seasons, state-level vaccination coverage showed an inconsistent association with reported influenza case counts. Some seasons suggested that higher vaccination rates corresponded to lower influenza case counts, while others showed the opposite. These inconsistencies are likely due to confounding factors such as population size, testing volume, and varying surveillance intensity. These findings underscore the complexity of interpreting real-world public health data and emphasize the importance of context-specific analysis for each season.

### Public Health Context
This project is an example of real-world evidence (RWE) and public health surveillance workflows commonly used to evaluate population-level interventions. It demonstrates how statistical modeling, analysis, and careful interpretation are required when working with observational healthcare data to avoid misleading conclusions.

### Tools
R, dplyr, janitor, ggplot2
