# Stroke-Prediction

### Introduction
This report was made as a final capstone project by our group in the Data Analytics class of HerTechTrail Community. The project centers on stroke prediction considering some of the key indicators. The importance of this analysis is to help individuals who are not living with stroke identify the risk factors they already have, and how to manage them in order to prevent having it in the future.

### Aims and Objectives
This report is provided to give actionable insights from the analysis of the data gathered concerning stroke patients. The insights obtained will help us know the risk factors associated with stroke. Some of these factors can be modified while some cannot be modified. Risk factors for stroke that can be modified include hypertension, heart disease, glucose level, lifestyle (smoking), and body mass index. The aim of our project is to analyze an existing dataset to effectively predict stroke based on these modifiable risk factors. This analysis will help alert individuals at risk on how to maintain a healthy lifestyle in order to avoid these risk factors.

### Data Sources
For this analysis, the data set was gotten from Kaggle. Kaggle is a well-known Machine Learning and Data Science community, which is made accessible for community data and code. [Download Here](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset)

### Tools and Libraries
For ease of collaboration, all our project files were saved on google drive. Our raw dataset was downloaded in a csv format and we used Excel to separate it into columns. After which this was imported into a Google Collab notebook for coding. Python was adopted as our programming language for this analysis. We kicked off by cleaning our data. We dropped some null values, assigned the appropriate data type where necessary and added columns to group continuous data for easy analysis. We import libraries such as pandas, seaborn and matplotlib for effective analysis and visualization. For effective communication of our findings to the target audience, we came up with this report using google docs and a presentation on google slides.

### Data Cleaning/Preparations
In the initial data prepartion, we performed the following tasks;
1. Data download and inspection
2. Data modification (From text to colums)
3. Data importation to Google Collab for coding

### Exploratory Data Analysis

EDA involved exploring the Stroke Prediction data to answer key data like;

- Which gender is more prone to stroke?

- How does marital status contribute to the chances of having  stroke?

- Does body mass index increase the risk of stroke?

- Which age group are more prone to stroke?

### Data Analysis

Some interesting codes/features we worked with;

```Python
import matplotlib.pyplot as plt
import seaborn as sns
import pandas as pd
import os
%matplotlib inline
```

``` python
df = pd.read_excel(path)
df.head(5)
```

``` python
newtype = df2['age'] = df2['age'].astype('int')
f"New datatype for age : {newtype.dtypes}."
```

### Conclusion

The analysis results are summarised as follows;
- There is a correlation between married people and the population of stroke
- Female patients with stroke are slightly more than male patients with stroke.
- Underweight patients are not likely to have stroke.
- Stroke is not common in children.

### Recommendations

Based on the analysis, we recommend the following action;

People in the private sector should take caution and manage their working habits, prioritize their health considering that the private sector registers more stroke patients compared to the other sectors.

### Limitations
- Strong imbalances exist in the dataset that is provided. Out of 4,909 individuals, only 209 had confirmed strokes, while the remaining 4,700 patient records indicated no evidence of a stroke.
- As noted in Kaggle by the author, the actual source of the data is confidential, as a result of this that, the region the data was gathered is not available. This may impact the conclusions drawn from the dataset. For instance, the climate conditions of a particular region may affect an individual’s health thereby impacting on stroke. This may not be so in other regions.
- Also, the data may be specific to the respondents as such it may not be appropriate to generalize the conclusions.
- The project completion was largely constrained on time.


