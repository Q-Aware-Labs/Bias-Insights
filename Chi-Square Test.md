A chi-square (Goodness of fit) test is used to compare the observed frequencies with the expected frequencies in a dataset. The Chi-Square test will give you a p-value that you can use to determine whether the difference between the observed and expected frequencies is statistically significant.

The formula to execute the chi-square test is:

![enter image description here](https://github.com/antonyga/Bias-Insights/blob/main/Media/Chi-square%20test%20main%20formula.png?raw=true)

Before we start operating with the formula we need to determine some values:

**Degree of Freedom:**

Degrees of freedom are the maximum number of logically independent values, which may vary in a data sample. 
Degrees of freedom are calculated by subtracting one from the number of items within the data sample.

As we have 8 categories, our Degree of Freedom is 7 (because 8 - 1).

**Observed Frequency (OF):**
The observed frequencies are the actual number of individuals in each age group in your dataset. 

**Expected Frequency (EF):**
The expected frequencies are what you would expect if there was no age bias.

To determine the actual values for OF and EF I have generated the following table:
Each ethnic group is expected to have at least 5 individuals aged over 60.

![enter image description here](https://github.com/antonyga/Bias-Insights/blob/main/Media/Observed%20Frequency%20vs%20Observed%20Frequency%20Table.png?raw=true)


![enter image description here](https://github.com/antonyga/Bias-Insights/blob/main/Media/Observed%20Frequency%20vs%20Observed%20Frequency%20Table.png?raw=true)

After calculating the chi-square value, our next step is to evaluate the results using a probability table. In the first column, we find the degrees of freedom (DF), with our focus on row number 7.

![enter image description here](https://github.com/antonyga/Bias-Insights/blob/main/Media/Probability%20Level%20Table%202.png?raw=true)

Our critical value is determined to be 14.067.

![enter image description here](https://github.com/antonyga/Bias-Insights/blob/main/Media/Probability%20Level%20Table%203.png?raw=true)

The final step involves comparing our calculated chi-square value with the critical value from the table. If the chi-square value exceeds the critical value significantly, we accept our hypothesis as valid.

In this specific case, the statement holds true, leading us to conclude that there exists a significant bias in the age subcategory of individuals aged 60 and above.

It’s important to note that a language model trained solely on this dataset may exhibit unexpected behavior when recognizing or generating images of individuals older than 60 years old.

  **DISCLAIMER:**

The findings presented in this project are based on rigorous analysis and interpretation. However, it is essential to recognize that these results are not official or universally applicable. Variations may exist due to factors such as sample size, data quality, and specific context.

Therefore, exercise caution when interpreting and applying these findings. Consider them as valuable insights rather than definitive conclusions. If you intend to use these results for any practical purposes, seek additional validation and consult domain experts.

Remember that statistical analyses provide valuable information, but they do not replace critical thinking, domain knowledge, and context-specific considerations.


REFERENCES:

https://www.youtube.com/watch?v=qYOMO83Z1WU

https://www.youtube.com/watch?v=WXPBoFDqNVk

https://sl.bing.net/gFFjvh4gcGi

https://www.investopedia.com/terms/d/degrees-of-freedom.asp

