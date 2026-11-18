A/B Testing — Recommendation System Evaluation

Project Overview

This project evaluates whether an improved recommendation system increases user conversion compared to the existing version.

The analysis uses A/B testing, conversion funnel analysis, exploratory data analysis, and statistical hypothesis testing to support a product decision.

Business Objective

Determine whether the improved recommendation system should be implemented based on its impact on user conversion.

Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Statistical hypothesis testing
- Jupyter Notebook

Project Structure

- "project_plan.ipynb" — Business problem definition, analytical objectives, KPIs, and analysis plan.
- "recommendation_system_ab_test.ipynb" — Data preparation, exploratory analysis, conversion funnel evaluation, and statistical testing.

Methodology

1. Data loading and quality assessment.
2. Data cleaning and preprocessing.
3. Exploratory data analysis.
4. Conversion funnel analysis:
   - Product page
   - Product cart
   - Purchase
5. A/B test evaluation using a Z-test for proportions.
6. Business conclusions and recommendations.

Key Findings

- 2,788 valid participants remained after excluding 887 users who participated in overlapping experiments.
- The experiment groups were unbalanced: 2,082 users in Group A and 706 in Group B.
- Group B showed lower conversion rates across all funnel stages:
  - Product page: 13.79% lower than Group A.
  - Product cart: 8.74% lower.
  - Purchase: 10.32% lower.
- The difference was statistically significant only at the product page stage.

Conclusion

The analysis found no evidence that the improved recommendation system increased conversion.

Data quality and experimental design limitations — including group imbalance, overlapping participants, users outside the target region, and possible incomplete event collection — should be addressed before running a new experiment.

Author

Gabriela Veriato
"GitHub Profile" (https://github.com/VeriatoG)
