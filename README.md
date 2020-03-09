This repository is a collection of jupyter notebooks in Python that I developed for recent projects.

Project 1: Unsupervised ML on NY Properties Anomaly Detection 				                                             

●	Created a business-level data quality report on NY property data with over 1 million records.
●	Leveraged google API and web scraping to fill in missing location data using Python; created and normalized expert variables by dividing averages at different granularities; optimized speed performance by applying vectorization.
●	Conduct principal component analysis to reduce dimensionality; visualized component variance explained; standardized principle components and calculated Euclidean distances of z-scaled components; built an autoencoder model and calculated Euclidean distances of the difference between inputs and decoded outputs; ranked by each score to unify scales and combined two rankings. 
●	Detected potential anomalies, traced down possible causes and created a high-level business report.

Project 2: Supervised Real Time Identity Fraud Model on Product Applications	                                                   

●	Produced exploratory data analysis report on 1 million product application records with fraud labels; cleaned frivolous fields. 
●	Applied smooth transition function to create a risk table of fraud probabilities at each day of the week at proper granular levels.
●	Created over 300 candidate time series variables; improved execution speed of professor’s script by 110x; achieved the best execution performance in the class.
●	Applied feature selection methods such as Kolmogorov–Smirnov, fraud detection rate, stepwise logistic regression, and Lasso regularization to reduce dimensionality; split dataset into training/testing and out of time validation sets; built supervised KNN/tree-based/support vector machines/neural networks classification models and conduct grid search/random search for hyperparameter tuning; calculated/plotted goodness measures such as ROC, AUC, as well as bias-variance tradeoff.
●	Picked model with the highest fraud detection rate at 3% on the out of time validation set; produced a high-level business report.
