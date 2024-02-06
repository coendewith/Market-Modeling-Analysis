# Market-Modeling-Analysis
An analytical project showcasing market positioning modeling using anonymized data. Involves bias adjustment, dataset alignment, and market trend analysis. The methodology aligns internal truths with external samples for strategic insights

link to external data: https://drive.google.com/file/d/1vVabbT3Ivvc-Zrpd8e9QHuSy9Jajlzdp/view?usp=sharing

## Project Overview
This project, titled "Market-Positioning-Analysis-Project," is a comprehensive exercise in market modeling and competitor analysis. It's focusing on competition insights. The dataset is anonymized. 

## Objective
The primary objective is to evaluate the internal organization's market position relative to its competitors using two datasets:

internal.csv: Internal ground truth figures of the internal organization.
external.csv: Anonymized external transaction data including the internal organization and its competitors.

## Methodology
The project involves several key steps:

### Data Bias and Quality Assessment
Time frames alignment for internal and external datasets.
Conversion of date columns to datetime objects.
Descriptive statistics comparison and visual data analysis for trend and variance discrepancies.
Application of bias adjustment methodologies, like Quantile alignment.
### Modeling Market Positioning
Historical weekly sales and orders modeling using both datasets.
Market position modeling for the internal organization and competitors.
Utilization of Python and Jupyter Notebooks for detailed analysis and visualization.
### Executive Insights
Presentation of competitive insights and strategic recommendations.
Focus on sales trajectories, performance benchmarks, and opportunities.

## Code Overview
The provided code covers various aspects of data preprocessing, analysis, and visualization:

Data reading and initial preprocessing.
Time frame alignment and weekly aggregation.
Descriptive statistics calculation.
Data comparison and visualization using Seaborn and Matplotlib.
Bias adjustment using Quantile alignment.
Sample size calculations and conversion of per-order data to total numbers.
Market positioning modeling and year-over-year change analysis.

## Key Assumptions
The bias in the external dataset is consistent across competitors.
The external dataset's sample size is representative across all players.

## Usage
1. Clone the repository to your local machine.
2. install requirements.txt
3. Run the Jupyter Notebooks to view the analysis and visualizations.

