# Apple-Store-Reviews


This repository contains a comprehensive statistical analysis of the Apple Store Reviews dataset. The analysis focuses on understanding user ratings, purchase amounts, likes, and correlations to uncover meaningful insights. The project is fully implemented in Python and includes visualizations, statistical calculations, and hypothesis testing.

# Project Overview
The project explores several core statistical topics applied to the Apple Store Reviews dataset, including:

• Central Tendency Analysis (Mean, Median, Mode)

• Spread of Data (Range, Interquartile Range)

• Variability Analysis (Variance, Standard Deviation)

• Correlation Analysis (Likes vs. Ratings)

• Distribution Analysis (Skewness of Ratings)

• Hypothesis Testing (Instagram vs. WhatsApp Ratings)

• Demonstration of the Central Limit Theorem (CLT)

# Analysis Details

1.Central Tendency Analysis

Objective: Identify the best measure of central tendency for app ratings.

Mean: 2.869

Median: 3.0

Mode: 1.0

Conclusion:

• The median is the best representative measure because it is less influenced by outliers compared to the mean.

2.Spread of Data

Objective: Measure the spread of purchase amounts using Range and Interquartile Range (IQR).

Range: 19.97

IQR: 10.19

Conclusion:

• The Range indicates the full spread between the smallest and largest purchases.

• The IQR focuses on the middle 50%, giving a clearer picture of typical purchase amounts.

3.Variability Analysis

Objective: Assess variability in user engagement (number of likes).

Variance: 822.85

Standard Deviation: 28.69

Conclusion:

• The relatively high standard deviation shows significant variability—some reviews receive very few likes, while others get a lot.

4.Correlation Analysis

Objective: Determine the relationship between likes and ratings.

Correlation Coefficient: 0.8425

Conclusion:

• A strong positive correlation exists—higher ratings tend to attract more likes, showing user preference for highly-rated content.

5.Distribution Analysis

Objective: Analyze the shape and skewness of app ratings distribution.

Skewness: 0.102

Conclusion:

• The distribution is approximately symmetrical with a slight positive skew. This indicates balanced user satisfaction, with a small tendency toward higher ratings.

6.Hypothesis Testing: Instagram vs WhatsApp Ratings

Objective: Test if Instagram’s average rating is significantly higher than WhatsApp’s.

Instagram Mean Rating: 2.77

WhatsApp Mean Rating: 2.93

T-Statistic: -0.797

P-Value: 0.787

Conclusion:
• With a p-value > 0.05, we fail to reject the null hypothesis. There is no significant difference between Instagram’s and WhatsApp’s average ratings.

7.Central Limit Theorem (CLT) Demonstration

Objective: Build a sampling distribution to validate the CLT.

Population Mean: 2.869

Sampling Mean: 2.878

Standard Error: 0.268

Conclusion:

• The sampling distribution is approximately normal, even if the population distribution isn’t.

• This supports the Central Limit Theorem, which states that the distribution of sample means approaches normality as sample size increases.

# Key Learnings

• Median is often a more robust measure of central tendency when data contains outliers.

• Correlation analysis can reveal important user behavior insights, like the relationship between ratings and likes.

• Hypothesis testing helps validate assumptions with statistical rigor.

• Demonstrating the Central Limit Theorem reinforces why sample-based inference works reliably.

# Tools & Libraries Used
• Python

• pandas

• numpy

• matplotlib

• seaborn

• scipy

• random
