## Heterogeneous Ensemble Classifier

### Insights 
* Preprocessing: Both datasets underwent preprocessing by removing irrelevant columns (CustomerId in churn and children in insurance). No missing values were found in either dataset.

* Test/Training Split: The datasets were split into training and testing sets, with a 0.2 test fraction.

* Ensemble Classifier: A heterogeneous ensemble classifier was constructed, consisting of three base classifiers: RandomForestClassifier, DecisionTreeClassifier, and LogisticRegression. A VotingClassifier with a hard voting scheme was employed. The random forest classifier had 50 estimators, while the decision tree classifier had a maximum depth of 5.

* Evaluation Metrics: Model performance was evaluated using accuracy, precision, recall, and F1 score. Higher accuracy values indicate better performance, while lower accuracy values indicate a weak ensemble.

* Churn Model vs. Insurance Model: The churn model produced impressive results with high accuracy, indicating a strong ensemble, while the insurance model produced average values.

### conclusion
The results suggest that the random forest classifier with a heterogeneous ensemble was effective on the churn dataset, while the performance on the insurance dataset was average.
