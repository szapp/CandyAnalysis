# Candy Analysis

Case study: Analyze the [candy power ranking](https://github.com/fivethirtyeight/data/tree/master/candy-power-ranking) to identify and recommend popular candy characteristics.

The dataset by FiveThirtyEight is distributed un the Creative Commons Attribution 4.0 International license (https://creativecommons.org/licenses/by/4.0/).

## Project

The production of a new candy is planned.
Among the project team there is no consensus about the characteristics of the candy.

Based on a dataset from market analysis, the task is to give a clear recommendation for what characteristics the new product should express.

## Deliverable

The results are compiled in a [presentation](Presentation.pdf) with a clear recommendation.
The presentation is in German, but the numbers speak for themselves.

<div align="center">
<img src="https://github.com/user-attachments/assets/3a7f5069-f299-4b35-95c1-1d13146ae950" width=400> <img src="https://github.com/user-attachments/assets/ea37f378-6052-496f-b6de-6070cbe091e1" width=400>
<br>
<img src="https://github.com/user-attachments/assets/224de4a4-b659-4a43-8244-dc814a8173b0" width=400> <img src="https://github.com/user-attachments/assets/e6e38600-ea02-4107-b738-cd5a5b72e42e" width=400>
</div>

## Libraries used

- Scipy
- Scikit-learn
- Seaborn

<sup>*See [requirements.txt](requirements.txt).*</sup>

## Challenges

- Small dataset (86 rows/samples)
- Data is aggregated over brands (e.g. win percentage)
- Study design might not be fair (not blind)

## Approach

Treating the problem not as a regression but as a classification and using statistical analysis allows to identify features that are statistically dependent with popular brands.
With interaction terms, the combination of successful characteristics can be recommended.
