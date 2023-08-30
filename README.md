# Loan-Approval-Classification
Welcome to the Loan Approval Prediction project!
Markup 
* Developed a machine learning models that assesses the likelihood of an individual's loan approval. 
* The model on a diverse dataset containing information about various individuals with different financial statuses and their historical loan personal information,
* Enabled to discern patterns that influence loan approval decisions.
# Data
The loan approval dataset comprises financial records and related data utilized to assess the qualification of individuals or entities for securing loans from a lending institution. This dataset encompasses diverse variables like credit scores, income, employment standing, loan duration, loan amount, asset valuation, and loan approval status.
# Results
Rank | model |	Root Mean Squared Error |	Accuracy on Traing set |	Accuracy on Testing set
-----|------|-------------------|------------------------------|-------------------------
3 |	MLPClassifier |	0.763635 |	39.502196 |	41.686183
7 |	KNeighborsClassifier |	0.670559 |	72.445095 |	55.035129
4 |	AdaBoostClassifier |	0.181071 |	97.920937 |	96.721311
5 |	ExtraTreesClassifier |	0.171096 |	100.000000 |	97.072600
0 |	DecisionTreeClassifier |	0.149158 |	100.000000 |	97.775176
6 |	GradientBoostingClassifier |	0.149158 |	99.472914 |	97.775176
1 |	XGBClassifier |	0.141090 |	100.000000 |	98.009368
2 |	RandomForestClassifier |	0.141090 |	100.000000 |	98.009368
Markup : ![picture alt](https://github.com/KhuranaAksh/Loan-Approval-Classification/blob/a99ff7735bdf034c369546ce9bf7bfb2fbeb32ff/F1Scores.JPG/200x150 "F1 Scores")
