# Project Title: Online Store Marketing A/B Test & Hypothesis Prioritization Analysis

**Overview:** This project focuses on the analysis and prioritization of marketing hypotheses and A/B testing to increase the revenue of an online store. The goal is to prioritize hypotheses using the ICE and RICE frameworks, analyze an A/B test for statistical significance, and provide data-driven recommendations for improving revenue. The project consists of two parts: hypothesis prioritization and A/B test analysis.

**Key Skills & Concepts:**

* Data Preprocessing: Cleaned and prepared datasets related to hypotheses, orders, and visits, addressing any anomalies and ensuring data consistency.
* ICE and RICE Frameworks: Applied both ICE and RICE frameworks to prioritize marketing hypotheses and compare their rankings.
* A/B Test Analysis: Analyzed A/B test data, including cumulative revenue, order size, conversion rates, and statistical significance testing.
* Anomaly Detection: Identified and filtered out anomalies by calculating the 95th and 99th percentiles for orders and order prices.
* Data Visualization: Created various visualizations (cumulative revenue, conversion rates, scatter plots) to compare A/B test groups.

**Key Insights:**

* Hypothesis Prioritization: The RICE framework re-prioritized hypotheses compared to ICE by factoring in user reach, which changed the ranking of key initiatives.
* A/B Test Results: Group B showed a significant increase of 18.9% in the conversion rate compared to Group A, even though no significant difference was found in average order size.
* Statistical Significance: Hypothesis testing showed that Group B outperformed Group A in terms of conversion rate, while no substantial difference was observed in average order size.
* Recommendations: The changes tested in Group B should be implemented across the store due to the increase in conversion rate, while further A/B testing is recommended for order size optimization.

**Tools Used:**

* Python (Pandas, Matplotlib): Data manipulation and visualization.
* Hypothesis Testing (SciPy): Statistical testing to analyze the significance of A/B test results.
* ICE & RICE Frameworks: Applied for hypothesis prioritization.
