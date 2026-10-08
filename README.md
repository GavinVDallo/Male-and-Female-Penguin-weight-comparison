# Male-and-Female-Penguin-weight-comparison
Similar to the previous repository I made, this time with inserting code or anything to add in readme
# Formative Assessment 5 (FA 5) - Linear Models: Palmer Penguins

Gavin Manuel V. Dallo (Solo/Individual)

This repository contains a comprehensive statistical analysis investigating factors that predict body mass in Palmer Penguins. The project evaluates main effects and complex interaction structures through analysis of variance (ANOVA) and linear regression framework modeling systems.

## 🎯 Research Question
> **Does penguin body mass differ according to species and sex, and does the effect of species on body mass depend on sex?**

---

## 📂 Repository Structure
*   **`data/`**: Contains the raw data file (`penguins.csv`) sourced from the official Allison Horst repository.
*   **`R/`**: Holds the primary analytical script file (`FA5_Linear_Models.Rmd`) containing step-by-step statistical procedures.
*   **`figures/`**: Holds automatically exported visualizations summarizing key variable patterns:
    *   `body_mass_by_species.png`: Segmented structural data boxplot distributions.
    *   `species_sex_interaction.png`: Intersecting line graphs validating structural model interaction dynamics.
*   **`report/`**: Contains the final rendered file (`FA5_Linear_Models.pdf`) showing comprehensive data printouts.

---

## 📊 Key Findings

### 1. Main Structural Predictors
*   **Species Variation**: Gentoo penguins exhibit the highest average overall body mass across all data fields. Adelie and Chinstrap penguins show significantly lower, relatively comparable mass profiles.
*   **Sex Demographics**: Across all evaluated categorical dimensions, male penguins consistently show higher body mass boundaries than their female counterparts.

### 2. Interaction Effect Stability
Our analysis confirms a **statistically significant interaction effect** (F(2, 327) = 8.76, p = 0.000197) between Species and Sex. This proves that the precise impact of sex variations on penguin weights fluctuates noticeably by species group:
*   **Gentoo**: Displays the largest male-to-female weight gap (~805g variation profile).
*   **Chinstrap**: Displays the narrowest male-to-female weight gap (~412g variation profile).

### 3. Explanatory Capacity
The full interactive linear model accounts for approximately **81.4%** of the observed variation in penguin body mass, showcasing high reliability and predictability metrics.

---

## 💻 How to Reproduce This Analysis
1. Clone this repository to your local system environment.
2. Open the project folder structure inside **RStudio**.
3. Compile the file structure inside the `/R` directory using the global **Knit** workflow to regenerate all matching output materials.
