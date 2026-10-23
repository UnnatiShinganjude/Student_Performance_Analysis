
Student Performance Analysis

Project Overview

This project explores student academic performance using Python and exploratory data analysis (EDA). It investigates how average scores vary across subjects and how academic performance is associated with factors such as gender, parental education level, lunch type, test preparation course completion, and race/ethnicity group.

The goal is to identify meaningful patterns in the dataset, communicate findings through visualizations, and develop practical data analysis skills.

Objectives

- Understand and explore a student performance dataset.
- Perform data quality checks and descriptive statistical analysis.
- Compare student performance across Mathematics, Reading, and Writing.
- Investigate associations between academic scores and selected categorical variables.
- Analyze relationships between subject scores using correlation analysis.
- Present findings through clear visualizations and evidence-based conclusions.

Dataset

The dataset contains 1,000 student records and the following original features:

| Feature | Description |
|---|---|
| `gender` | Student gender |
| `race/ethnicity` | Student's race/ethnicity group |
| `parental level of education` | Parent's education category |
| `lunch` | Lunch category |
| `test preparation course` | Test preparation completion status |
| `math score` | Mathematics score |
| `reading score` | Reading score |
| `writing score` | Writing score |

Two additional features were engineered during the analysis:

- Average Score:Mean of the Mathematics, Reading, and Writing scores.
- Performance Category:A category based on average score: Low Performer (below 60), Average Performer (60 to below 80), or High Performer (80 and above).

These performance categories use project-defined thresholds and are not official academic classifications.

Tools and Technologies

- Python — Programming language
- Pandas — Data manipulation and analysis
- NumPy — Numerical operations
- Matplotlib** — Data visualization
- Seaborn — Statistical visualization
- Jupyter Notebook — Interactive analysis environment
- VS Code — Development environment

Project Workflow

1. Defined the project objective and explored the dataset.
2. Inspected the dataset structure, column names, and data types.
3. Checked for missing values and duplicate records.
4. Generated descriptive statistics.
5. Created the Average Score and Performance Category features.
6. Performed univariate analysis to examine score distributions.
7. Conducted group comparisons across demographic and educational factors.
8. Used bar charts, boxplots, histograms, scatter plots, and a correlation heatmap to explore patterns.
9. Summarized findings, interpretations, and limitations.

Key Findings

1. Overall Student Performance

- Number of student records: 1,000
- Mean average score: 67.77
- Median average score: 68.33
- Standard deviation: 14.26

Using the project-defined performance categories:

- Average Performers: 51.7%
- Low Performers: 28.5%
- High Performers: 19.8%

2. Subject-wise Performance

| Subject | Mean Score |
|---|---:|
| Reading | 69.17 |
| Writing | 68.05 |
| Mathematics | 66.09 |

Reading had the highest mean score, while Mathematics had the lowest.

3. Test Preparation Course

| Test Preparation Status | Mean Average Score |
|---|---:|
| Completed | 72.67 |
| None | 65.04 |

Students who completed the test preparation course had a mean average score 7.63 points higher than students who did not complete it.

4. Parental Education Level

- Highest mean average score: Master's degree — 73.60
- Lowest mean average score: High school — 63.10

The results show differences in average scores across parental education categories.

5. Lunch Category

| Lunch Category | Mean Average Score |
|---|---:|
| Standard | 70.84 |
| Free/reduced | 62.20 |

The standard-lunch group had a mean average score 8.64 points higher than the free/reduced-lunch group.

6. Gender Comparison

Female students had a higher overall mean average score in the analysis, although the differences varied by subject.

7. Race/Ethnicity Group Comparison

- Highest mean average score: Group E — 72.75
- Lowest mean average score: Group A — 62.99

These are descriptive differences within the dataset and do not explain their underlying causes.

8. Correlation Between Subjects

| Subject Pair | Correlation |
|---|---:|
| Reading and Writing | 0.955 |
| Mathematics and Reading | 0.818 |
| Mathematics and Writing | 0.803 |

All three pairs showed strong positive linear relationships. Reading and Writing had the strongest correlation.

Limitations

- The analysis is observational and does not establish causal relationships.
- The dataset does not contain variables such as attendance, weekly study hours, or previous academic performance.
- Group differences may be associated with other factors not captured in the dataset.
- Statistical significance was not established through formal hypothesis testing.
- Performance categories use thresholds selected for this project.

Conclusion

This project demonstrates how exploratory data analysis can uncover patterns in student academic performance. Reading had the highest average score, and Reading and Writing scores showed the strongest correlation. Differences were also observed across test preparation status, parental education categories, lunch categories, gender, and race/ethnicity groups.

These findings provide a starting point for further statistical investigation. They should be interpreted as associations within the dataset rather than proof of causation.

 How to Run the Project

1. Clone or download this repository.
2. Open the project folder in VS Code.
3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Open the Jupyter notebook in the `notebooks/` directory.
5. Ensure the dataset is available at the file path referenced in the notebook.
6. Run the notebook cells in order.

Skills Demonstrated

- Data loading and inspection
- Data quality assessment
- Feature engineering
- Descriptive statistics
- Univariate and bivariate analysis
- Group-based comparisons
- Correlation analysis
- Data visualization
- Analytical interpretation and reporting

---

Author: Unnati Shinganjude

Project Type:Exploratory Data Analysis (EDA)