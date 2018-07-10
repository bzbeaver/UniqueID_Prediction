# UniqueID_Prediction

Problem Definition: Client wants to predict successful all “unique Ids” from unique Id
column who have high chance of getting 1 as “Target” column value.

2. Input Two Datasets:
a) Training – train.csv
b) Testing – test.csv

3. Train/Test Data Schema:
a) &#39;Target&#39; Column in the training set is Class Label. “-1” signifies missing value in the columns.
b) TOP means Time on Page in seconds
c) Exits means number of times unique Id has exited the page
d) Binary_Var contains binary values
e) Metric_Var contains continuous values
f) Unique Id is the primary key/unique identifier
g) Page1_Visited means whether unique id has visited the page or not

4. Metrics of Evaluation
a) Confusion Matrix
b) F1 Score
c) Accuracy Score
d) AUC_ROC_Score
d) The code must be clearly commented. Visualizations are optional
PS: The column names have been changed; some column values have been hashed for data confidentiality reasons. Test and Train Files are compressed and attached.
