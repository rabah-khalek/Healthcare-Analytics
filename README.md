# Healthcare-Analytics
Contents of Repository:
- Python Notebook file contains project code for Data Exploration, Feature Engineering, and Machine Learning models (Naive Bayes, XGBoost, Neural Networks).
- PDF Report file contains overview of the project, predicitions and results.
- Datasets.zip contains both the test and train data used in the project.
- HTML file is a markdown of the jupyter notebook with alll the outputs to View without python or its IDE.

Introduction:

  Healthcare organizations are under increasing pressure to improve patient care outcomes and achieve better care. While this situation represents a challenge, it also offers organizations an opportunity to dramatically improve the quality of care by leveraging more value and insights from their data. Health care analytics refers to the analysis of data using quantitative and qualitative techniques to explore trends and patterns in the acquired data. While healthcare management uses various metrics for performance, a patient’s length of stay is an important one.

  Being able to predict the length of stay (LOS) allows hospitals to optimize their treatment plans to reduce LOS, to reduce infection rates among patients, staff, and visitors.

Project Highligths:

Hospital admission data was analyzed to accurately predict the patient’s Length of Stay at the time of admit so that the hospitals can optimize resources and function better. Built 3 models in Python to predict the length of stay,

-	A supervised algorithm Naïve Bayes which was classifying with an accuracy of 34.55%.

-	An ensemble method XGBoost which was predicting with an accuracy of 43.05%.

-	A dense neural network with 6 layers which yields an accuracy of 42.5%.

Bias, Risks, and Limitations:

The model was analyzed with [Giskard](github.com/giskard-AI/giskard) and the following limitations were identified:

- [Performance issues](https://docs.giskard.ai/en/latest/getting-started/key_vulnerabilities/performance_bias/index.html) (12): The model exhibits low precision across different groups or segments of the data.
- [Overconfidence issues](https://docs.giskard.ai/en/latest/getting-started/key_vulnerabilities/overconfidence/index.html) (3): The model produces predictions that are incorrect but are assigned high probabilities or confidence scores.
- [Underconfidence issues](https://docs.giskard.ai/en/latest/getting-started/key_vulnerabilities/underconfidence/index.html) (13): The model produces predictions with low confidence, even when the true label is highly likely.

A full report is available [here](https://htmlpreview.github.io/?https://github.com/rabah-khalek/Healthcare-Analytics/blob/ece49dc742b355e4cc2498a558fb364c1c0a6e78/reports/2023.10.23-16.16.56.html).
