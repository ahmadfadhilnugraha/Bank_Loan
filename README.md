# Bank Loan

My task is to prepare a report for the credit division of a bank. You will investigate the impact of a customer's marital status and the number of children they have on the probability of default in loan repayments. The bank already has some data regarding the creditworthiness of its customers.

This report will be considered when making credit assessments for potential customers. Credit assessments are crucial in evaluating the ability of prospective borrowers to repay their loans.

## Goals

In this meticulous data science project, I am delving into a comprehensive analysis of credit risk, specifically focusing on factors such as a customer's marital status and the number of children they have. These factors have the potential to significantly influence a customer's ability to settle loans and impact the probability of default in loan payments. Therefore, it is imperative to comprehend how these factors affect credit risk and take appropriate measures to mitigate such risks. As part of this exploration, I am formulating and testing four hypotheses:

1. Correlation between Having Children and Probability of Loan Default: Investigating whether having children is correlated with an increased likelihood of loan default.

2. Correlation between Family Status and Timely Repayment: Exploring whether a customer's family status is correlated with their ability to make timely loan repayments.

3. Correlation between Income Level and Timely Repayment: Analyzing whether a customer's income level correlates with their likelihood of repaying loans on time.

4. Impact of Loan Purpose on Default Rate: Assessing how the stated purpose of a loan influences the default rate.

This project holds significance not only for academic purposes but also for practical applications within the banking sector, contributing to a deeper understanding of credit risk and aiding in the development of effective risk mitigation strategies.

## Steps

The data related to users behavior is stored in the file /datasets/credit_scoring_eng.csv

This projects will consist of 3 steps:

1. Data Exploration
2. Data Cleaning
3. Hypotheses Testing
4. Conclusion and Recommendation

## Conclusion

**Conclusions Drawn from Data Processing:**

* Missing data in the provided dataset does not exhibit discernible patterns.
* Missing values are filled using either the mean or median, determined by the data distribution in each respective column.
* Duplicate entries in the data are handled by eliminating redundant records.

**Key Observations and Insights:**

* Customers with dependent children tend to have a higher probability of loan default (9.2%).
* Unmarried customers display an elevated tendency toward loan default (9.7%).
* Customers with a moderate to high income level exhibit a heightened likelihood of loan default (9.0%).
* Loans for education payments are associated with a higher default rate (>10%).
* The highest likelihood of default is observed among customers with a loan purpose for supplementary education, with a rate of 11.5%.

## Future Work

In future analyses, it would be beneficial to explore additional variables or refine existing ones to gain a more nuanced understanding of credit risk. Additionally, conducting a deeper investigation into the specific characteristics of loans for supplementary education and their impact on default rates could provide valuable insights. Regular updates to the analysis, incorporating new data and refining methodologies, will ensure the ongoing relevance and accuracy of the credit risk assessment process.

