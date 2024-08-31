# Exploring the Complex Relationship Between Income Levels and Mental Health: Insights and Realities
## Introduction
Mental health is a crucial social issue that needs clear attention. Mental health problems have various causes, and a person's overall health depends on their physical, social, and mental well-being. We are particularly interested in studying how a person's history of mental illness is linked to their income. While it's commonly believed that lower income is associated with higher levels of mental illness due to financial stress and limited resources, the reality is more complex. This project aims to examine the intersection of income and mental health by using KMeans clustering to identify patterns among respondents based on their income levels and history of mental illness.

>[!TIP]
>For a deeper dive into the data and methods used in this project, please check out the <code>Income_MentalHealth_Analysis.ipynb</code> notebook. Whether you're interested in the technical details or the insights derived from the analysis, the notebook provides a comprehensive overview of the entire project.

## Communicate Results
<img width="1337" alt="Screenshot 2024-08-31 at 10 42 29 AM" src="https://github.com/user-attachments/assets/94315a6e-0b51-474b-9774-dc41b7d3e916">
A visual representation of the clusters, captured from the Notebook <code>Income_MentalHealth_Analysis.ipynb</code>

### Interpretation
*Cluster 0* : This represents the group of people without a history of mental illness.

- **Medium Income**: This is the most represented income group in this cluster, with a value of 0.44.
- **High Income**: Has moderate representation, with a value of 0.29.
- **Low Income**: Has slightly lower representation than high income, with a value of 0.27.

*Cluster 1* : This represents the group of people with a history of mental illness.

- **Medium Income**: Again, the most represented income group in this cluster, with a value of 0.45.
- **Low Income**: Moderately represented, with a value of 0.32.
- **High Income**: Least represented in this cluster, with a value of 0.23.

1. **High Income Group**

In the group of people without a history of mental illness, 29% are in the high-income category and in the other (with a history of mental illness) 23% are in the high-income category. This means that if someone has a high income, they are 6% more likely to be free from mental illness compared to those with lower income.

2. **Low Income Group**

In the group of people without a history of mental illness, 27% are in the low-income category and in the other (with a history of mental illness) 32% are in the low-income category. It tells us that if someone has a low income, they are 5% more likely to have a history of mental illness compared to those with higher income.

3. **Medium Income Group**

In the group of people without a history of mental illness, 44% are in the medium-income category and in the other (with a history of mental illness) 45% are in the medium-income category. This means that for the medium-income group, there is a very small difference between the two clusters—a 1% higher chance of being in the group with a history of mental illness. This suggests that, unlike with high and low income, the likelihood of having or not having a history of mental illness is almost evenly distributed among those in the medium-income group.

### Implications
**Targeted Interventions**: The results suggest the need for targeted mental health interventions:

- **For Low-Income Individuals**: Focus on improving access to mental health services, providing financial assistance, and building community support systems to help mitigate the risk of mental illness.
- **For High-Income Individuals**: Address the unique stressors associated with high-income lifestyles, such as work-related stress and social isolation, through mental health support tailored to these challenges.

**Further Research**: The findings also point to areas for further exploration:
- **Understanding Resilience**: Investigate what factors contribute to resilience among low-income individuals who do not develop mental illness, and explore how these factors can be strengthened in at-risk populations.

### Important Considerations
While the analysis shows general trends—such as people with higher incomes being more likely to be free from mental illness—this doesn't apply to everyone.

Even though high income is generally linked to better mental health outcomes, it's crucial to recognize that 23% of the people in the group with a history of mental illness are still in the high-income category. This means that mental illness can affect anyone, regardless of their financial status. Similarly, while the data suggests that lower income might be associated with a higher risk of mental illness, there are still many individuals with low income who do not experience mental health issues. In the group without a history of mental illness, 27% of people are in the low-income category.

Mental illness doesn't discriminate based on income, and people from all walks of life can experience it. While income might be one factor, it's not the only one, and it's important to approach mental health with a full understanding of its many dimensions.
