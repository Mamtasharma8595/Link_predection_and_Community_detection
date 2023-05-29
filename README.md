# Graph Analysis and Link Prediction
This project focuses on analyzing a graph dataset and performing link prediction using various machine learning models.
## Dataset
The dataset used in this project is "fb-pages-food.edges" and represents connections between Facebook pages related to food.
## Graph Visualization
The initial step involves visualizing the graph to understand its structure and connectivity. The graph is plotted using the NetworkX and Matplotlib libraries.
## Link Prediction
Multiple machine learning models are employed for link prediction based on feature extraction using the Node2Vec algorithm.
## Logistic Regression
Logistic regression is utilized as a baseline model, and the classification report and ROC AUC score are calculated.
## CatBoost Classifier
The CatBoost Classifier is trained and evaluated for link prediction accuracy.
## XGBoost Classifier
The XGBoost Classifier is trained and evaluated for link prediction accuracy.
## LightGBM Classifier
The LightGBM Classifier is trained and evaluated for link prediction accuracy.
## Graph Visualization (Community Detection)
The Louvain algorithm is used for community detection within the graph, and the resulting communities are visualized using the PyVis library.
## Triadic Closure
Triadic closure is performed to identify possible new edges in the graph based on existing connections.
## Additional Analysis
Further analysis is conducted using the LightGBM model for predicting link probabilities and calculating precision and recall scores.

