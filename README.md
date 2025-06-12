This repository contains code and experiments for the paper:

# Automated Detection of Stigmatizing Language in Electronic Health Records (EHRs) Using a Multi-stage Transfer Learning Approach

## Abstract:
### Objective
Stigmatizing language in Electronic Health Records (EHRs) can perpetuate biases and negatively impact patient care. This study introduces a novel method for automatically detecting such language to improve healthcare documentation practices.

### Materials and Methods
We developed a multi-stage transfer learning framework integrating semantic, syntactic, and task adaptation. Experiments were conducted on 4,129 de-identified EHR notes (72.7% stigmatizing, 27.3% non-stigmatizing), split 80/20 for training and testing. Longformer, BERT, and ClinicalBERT models were evaluated, and model performance was assessed on 35 randomized subsets of the test set (each comprising 70% of test data). The Wilcoxon-Mann-Whitney test was used to evaluate statistical significance, with Bonferroni correction applied to control for multiple hypothesis testing. Baseline models included zero-shot and few-shot GPT-4o, Support Vector Machine, Random Forest, Logistic Regression, and Multinomial Naive Bayes.

### Results
The proposed framework achieved the highest accuracy, with fully adapted Longformer reaching 89.83%. Performance improvements remained statistically significant after Bonferroni correction compared to all baselines (p < .05). The framework demonstrated robust gains across different stigma types.

### Discussion
Our multi-stage transfer learning framework robustly outperformed all baseline models and generalized well across different stigmatizing language types. The use of Bonferroni correction confirms that improvements are statistically reliable. These results underscore the practical value of domain-adaptive approaches for automated bias detection in EHRs and support the adoption of responsible, fair AI in clinical documentation.

### Conclusion
This framework offers a statistically validated, high-performing solution for detecting stigmatizing language in EHRs, supporting responsible AI and promoting equity in clinical care.


# Codes and requirements
Thank you for your interest in the reproducibility of our work. We recognize the importance of open science and are committed to sharing our code to support transparency and further research. We are in the process of preparing the software source code for public release and will be ready soon.
