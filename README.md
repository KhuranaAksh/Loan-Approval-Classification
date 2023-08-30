# Loan-Approval-Classification
Welcome to the Loan Approval Prediction project!
Markup 
* Developed a machine learning models that assesses the likelihood of an individual's loan approval. 
* The model on a diverse dataset containing information about various individuals with different financial statuses and their historical loan personal information,
* Enabled to discern patterns that influence loan approval decisions.
# Data
The loan approval dataset comprises financial records and related data utilized to assess the qualification of individuals or entities for securing loans from a lending institution. This dataset encompasses diverse variables like credit scores, income, employment standing, loan duration, loan amount, asset valuation, and loan approval status.
# Results
S.No | model |	Root Mean Squared Error |	Accuracy on Traing set |	Accuracy on Testing set
-----|------|-------------------|------------------------------|-------------------------
1 |	MLPClassifier |	0.763635 |	39.502196 |	41.686183
2 |	KNeighborsClassifier |	0.670559 |	72.445095 |	55.035129
3 |	AdaBoostClassifier |	0.181071 |	97.920937 |	96.721311
4 |	ExtraTreesClassifier |	0.171096 |	100.000000 |	97.072600
5 |	DecisionTreeClassifier |	0.149158 |	100.000000 |	97.775176
6 |	GradientBoostingClassifier |	0.149158 |	99.472914 |	97.775176
7 |	XGBClassifier |	0.141090 |	100.000000 |	98.009368
8 |	RandomForestClassifier |	0.141090 |	100.000000 |	98.009368

![F1Scores](https://github.com/KhuranaAksh/Loan-Approval-Classification/assets/50616556/59734c14-9e0b-41cc-ba93-35c31821248e)

