# Heart-Attack

Using Python, pandas, seaborn, and scikit-learn, I analyzed a heart disease dataset sourced from an online repository. Initially, I meticulously cleaned the data to ensure accuracy and reliability, followed by comprehensive visualization to extract insights and patterns. Through exploratory data analysis, I identified potential factors influencing the presence of heart disease, paving the way for subsequent modeling.

Employing machine learning techniques, particularly logistic regression, I constructed predictive models to classify individuals based on their likelihood of having heart disease. Through rigorous evaluation, logistic regression emerged as the optimal model, showcasing robust performance without encountering overfitting or underfitting issues. Its ability to effectively capture the relationships between various features and heart disease outcomes, coupled with its interpretability, underscores its suitability for this classification task.

The success of logistic regression underscores the importance of selecting appropriate algorithms tailored to the dataset and problem domain. This comprehensive approach, spanning data preprocessing, visualization, modeling, and evaluation, highlights the power of Python libraries and tools in uncovering actionable insights from complex datasets. Ultimately, the application of logistic regression in this context enables informed decision-making in assessing heart disease risk factors and underscores the value of data-driven methodologies in healthcare analytics.

EDA Insights - 
In our analysis, we found distinct patterns related to various attributes, 
Males exhibited a higher prevalence of heart disease compared to females in the dataset.
Non-anginal pain showed a higher likelihood of heart disease compared to typical or atypical angina.
Lower fasting blood sugar levels (<120mg/dl) were more prevalent but did not significantly correlate with disease occurrence.
Normal resting electrocardiographic results often coincided with heart disease presence.
Exercise-induced angina indicated lower disease likelihood.
Upsloping ST segments were associated with reduced disease probability.
Downsloping segments suggested a higher risk of heart disease.
Individuals with no blockages but represented significantly had heart disease.
A reversible defect in thallium stress testing strongly correlated with heart disease, indicating reduced blood flow during stress but near-normal flow at rest.
