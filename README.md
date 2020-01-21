# DiabetesReadmission


The analyses is done for US Data 130 Hospitals for Diabetes and to figure out the factors contributing to diabetes and measures to prevent it from occurring and the medications that were used for readmissions




MODELLING 
Modelled in Logistic Regression(both in Lasso and Ridge ) methods and got a score of
0.4946362044975088 – F1-Score
0.6172491161272776 – Accuracy 
0.6029161142886882 – ROC_AUC Score 


INFERENCES 
Looking at the LIME explainer used on the Logistic Regression Model and checking for the feature importance on the  Ridge model , the factors that are contributing  to the readmissions are Acarbose, number_emergency, number_outpatients, number_diagnosis where as using metformin, insulin for specific cases reduces the chances of the readmission by patients . By dropping features such as diag_3,diag_1 ,diag_2 , A1Cresult   , numprocedures   which have less feature importance we can further tune the model to get a better prediction Rate.   

