# credit-risk-classification
----------------------------
# Overview of analysis 

The Purpose: Utilize logistic regression for the purpose of detecting conditions that could constitute a “high-risk” loan and then label prospective loans with said conditions for preventive measure.

# Results

•	The scores for this model: accuracy, precision, and recall all sit between .84 and 1.00. placing them all in positions of reasonable to high confidence and reliability.

•	The Accuracy scores for the model reflect its ability to be correct in all aspects of prediction, this specific model’s accuracy score is 0.99, near perfect in its overall correctness. 

•	The precision score of the model refers to its ability to predict members of the targeted class, 0 or 1 in this instance. A higher precision in one class means the model is correctly predicting the placement in that class and a lower precision simply means the opposite. This model’s precision for clustering in 0, which is a healthy loan agreement, at 1.00 precision and it clusters into 0, a high-risk loan agreement, at 0.84, which is marginally less precise more than likely due to a potential overtraining from an abundance of healthy loans compared to high-risk loans.

•	The model’s recall score is referencing the number of false positives recorded by the classification report, meaning that a lower score shows a false categorization by the model and a higher score shows an accurate and definite reporting. Once again, the model performs poorer at categorizing high-risk loans compared to healthy loans and the recall scores show this. 

# Summary

based on these results, I would be skeptical on implementing the model, the overtraining issue and near 20 percent loss of accuracy on high-risk loans could potentially lead to several false positives and improper labeling that may cause a loss of profit or opportunity due to turned denied loans. The model’s hyper efficient categorization of healthy loans more than likely means that a non-automated process could handle this analysis without risk of false labelling from automation with an overtrained model. 
  
