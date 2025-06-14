Twitter Trend Analysis:
Summary:-
The dataset analyzed is a Twitter sentiment dataset containing columns like Entity, Sentiment, and Tweet content, aiming to classify tweets based on sentiment (e.g., Positive, Negative, Neutral).

Initial data exploration included inspecting shape, basic statistics, and missing values.

The dataset includes multiple unique entities and sentiments, with a pie chart used for entity distribution and bar chart for sentiment distribution.

Missing values in Tweet content were handled using forward fill to retain data integrity.

Exploratory analysis included visualizations such as pie charts (for Entity), bar charts (for Sentiment), and a boxplot (for Entity frequency).

Label encoding was used to convert categorical values of Entity and Sentiment into numerical form for machine learning model compatibility.

Feature selection was done by dropping Tweet content, focusing only on Entity for model input and Sentiment as target.

Data was split into training and testing sets using an 80/20 split.

Two models were trained: Random Forest Classifier and Logistic Regression. Both were evaluated for training and test accuracy.

Confusion matrix and heatmap visualizations were used to evaluate model performance, indicating classification accuracy and error distribution.

Accuracy score and predicted probabilities from the model were also computed to assess effectiveness and confidence levels.
