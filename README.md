
# Comparison of K Distributions: Ants on the Picnic Blanket 🐜

## Project Overview
This project investigates the factors influencing ant attraction to sandwiches. Through statistical analysis, we examine the role of bread types, toppings, and butter presence in determining the average number of ants drawn to sandwiches. The study is based on the **SandwichAnts2** dataset and employs techniques like ANOVA, pairwise t-tests, and hypothesis testing.

## Dataset
The dataset, **SandwichAnts2**, contains 48 observations and the following variables:
- **Bread**: Types of bread (`wholegrain`, `multigrain`, `rye`, `white bread`)
- **Topping**: Sandwich toppings (`ham pickles`, `peanut butter`, `yeast spread`)
- **Butter**: Presence of butter (`with`, `without`)
- **Ants**: Number of ants observed

## Key Objectives
1. Determine whether bread type, toppings, or butter presence significantly affects ant attraction.
2. Validate assumptions for ANOVA tests.
3. Perform ANOVA and pairwise t-tests to assess the differences between groups.

## Statistical Methods
The following methods were employed:
- **ANOVA**: For comparing means across multiple groups.
- **Pairwise t-tests**: To analyze specific group differences.
- **The Bonferroni Method**: To control for multiple testing errors.
- **Hypothesis Testing**: To evaluate claims about group parameters.

## Tools and Libraries
The analysis was conducted using **R**, with packages such as:
- `haven`: Data import/export
- `dplyr`: Data manipulation
- `ggplot2`: Data visualization

## Findings
- **Bread Types**: No significant difference in ant attraction across bread types.
- **Toppings**: Significant differences found. `Ham pickles` attracted more ants than `peanut butter` and `yeast spread`.
- **Butter Presence**: Sandwiches with butter attracted significantly more ants.
