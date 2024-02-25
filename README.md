******* 🚧⚠️ PROJECT IS UNDER CONSTRUCTION ⚠️🚧 *********

**ABOUT THE PROJECT**

Bias Insights is a small Statistical Analysis Project for bias detection in a dataset before it is used to train a language model.
Decting bias in a dataset before it is used for training is a fundamental process in the development of a language model.

In this project I will be using the Chicago Face Database as my main dataset. 
This is a short description of the dataset published on their official web (https://www.chicagofaces.org/):

*"The Chicago Face Database was developed at the University of Chicago by Debbie S. Ma, Joshua Correll, and Bernd Wittenbrink. The CFD is intended for use in scientific research. It provides high-resolution, standardized photographs of male and female faces of varying ethnicity between the ages of 17-65. Extensive norming data are available for each individual model. These data include both physical attributes (e.g., face size) as well as subjective ratings by independent judges (e.g., attractiveness)."*

After observing the dataset, I have formulated the following hypothesis:

"The Chicago Face Database, while comprehensive, appears to have an underrepresentation of individuals aged 60 and above. This observed age bias could potentially impact the performance of machine learning models trained on this dataset, particularly in tasks involving the generation or recognition of faces belonging to this age group. Consequently, it is hypothesized that a model trained on this dataset may exhibit decreased accuracy and reliability when applied to faces of individuals older than 60 years old. This project aims to statistically validate this hypothesis and explore potential mitigation strategies to address this bias, thereby enhancing the model’s performance across all age groups."

To demonstrate whether my hypothesis is right or not I WILL use a statistical analysis thecnique called: chi-square test.

In the following page I will give details of every step.

A chi-square test is used to compare the observed frequencies with the expected frequencies. The Chi-Square test will give you a p-value that you can use to determine whether the difference between the observed and expected frequencies is statistically significant.

CHICAGO FACE DATABASE (CFD) DATASET  A C K N O W L E D G E M E N T 
CFD: Ma, Correll, & Wittenbrink (2015). The Chicago Face Database: A Free Stimulus Set of Faces and Norming Data. Behavior Research Methods, 47, 1122-1135. https://doi.org/10.3758/s13428-014-0532-5.
CFD-MR: Ma, Kantner, & Wittenbrink, (2020). Chicago Face Database: Multiracial Expansion. Behavior Research Methods. https://doi.org/10.3758/s13428-020-01482-5.
CFD-INDIA: Lakshmi, Wittenbrink, Correll, & Ma (2020). The India Face Set: International and Cultural Boundaries Impact Face Impressions and Perceptions of Category Membership. Frontiers in Psychology, 12, 161. https://doi.org/10.3389/fpsyg.2021.627678.

