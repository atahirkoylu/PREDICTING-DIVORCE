# Predicting Divorce
Inform a possible approach to sorting the GDPR’s encroachment.

# Project Objection

The objective of this project is to investigate which specific phrases or statements from a standardized dataset are the most predictive indicators of potential divorce. Using interpretability-focused data mining techniques—including Fast and Frugal Trees, 

LASSO (Least Absolute Shrinkage and Selection Operator), and One-R (One Rule algorithm)—the goal is to develop an informed and transparent model of decision-making. 
This project aligns with broader academic debates around the GDPR’s call for explainable AI by exploring simplified yet powerful prediction tools, specifically drawing from the Fast and Frugal heuristics proposed by Gigerenzer and Thin Slices theory as discussed by Malcolm Gladwell.

Ultimately, the project aims to deliver both a quantitative analysis and a qualitative reflection on how minimalist predictive models can be effective—and perhaps even preferable—when addressing sensitive human topics like marriage stability and divorce.

# Project Question

 -Which specific items or questions in the dataset most strongly predict divorce, based on LASSO regression results?

 -How does the Fast and Frugal Tree algorithm help simplify divorce prediction into a transparent, rule-based process?

 -Can One-R identify a single variable that offers surprisingly high predictive accuracy?

 -What are the similarities and differences in the predictors identified by each of the three algorithms?

 -To what extent do the most predictive questions align with insights from Gottman's work on marital breakdown?

 -How do Fast and Frugal approaches stand up to GDPR-style demands for algorithmic transparency and explainability?

 -Do models with fewer, more intuitive predictors yield better or worse accuracy compared to more complex models?

 -How might this predictive modeling be ethically applied in real-world scenarios involving relationships and counseling?

 -Are the most predictive statements more emotionally charged, factual, or behavioral in nature?

 -How does this project reflect the “Less is More” approach in predictive modeling, and what does it suggest about model simplicity versus complexity?

 # Model

  - Excel : was used for data cleaning
  - R : was used to analyse and apply methods to receive a result.

# Conclusion

  #Upon reviewing the results above, we find that all our models demonstrate strong performance. Notably, they exhibit similar outcomes in terms of recall, specificity and precision. Nevertheless, for this dataset, we have chosen the Random Forest model. This decision is primarily based on the higher accuracy observed in OOB results compared to the accuracy achieved by other models.

#In our model evaluation, we opted for the accuracy metric because it is well-suited for predicting both divorce and non-divorce outcomes. The ability to forecast potential divorces allows us to offer couples the opportunity to seek marriage counseling and reconcile their differences before the situation deteriorates. Conversely, predicting lasting marriages can help couples strengthen and maintain their relationships.

#This dataset and analysis aim to explore factors that contribute to the prediction of divorce or lasting marriages based on the Divorce Predictors Scale (DPS) from from 150 couples in Turkey, where the couples are categorized as either "divorce" or "not_divorce."

#Data preparation was a critical step, ensuring the correct data types and treating the target variable as a factor. The absence of missing values indicates that the dataset is relatively clean and ready for analysis.

#Our exploratory data analysis has provided a comprehensive summary of questionnaire attributes. The responses to various questions range from 0 to 4, and the mean values offer insights into response distribution. This initial exploration phase enhances our understanding of the data before proceeding with more advanced analyses.

#This dataset could be used for predictive modeling to develop a model that can predict whether a couple is likely to divorce or not based on their responses to the questionnaire. Various machine learning algorithms, such as Naive Bayes, Decision Trees, and Random Forest, could be applied to create predictive models. Understanding the factors contributing to divorce prediction can have significant implications for relationship counseling and support services.

#This dataset is a valuable resource for predictive modeling aimed at predicting whether a couple is likely to divorce based on their questionnaire responses. Machine learning algorithms, such as Naive Bayes, Decision Trees, and Random Forest could be employed to construct predictive models. Recognizing the factors contributing to divorce prediction has significant implications for relationship counseling and support services.
