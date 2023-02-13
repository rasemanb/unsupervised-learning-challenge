# unsupervised-learning-challenge

# Background 

You are on the data science team of a medical research company that’s interested in finding better ways to predict myopia, or nearsightedness. 
Your team has tried—and failed—to improve their classification model when training on the whole dataset. However, they believe that there might 
be distinct groups of patients that would be better to analyze separately. So, your supervisor has asked you to explore this possibility by using
unsupervised learning. You have been provided with raw data, so you’ll first need to process it to fit the machine learning models. You will use 
several clustering algorithms to explore whether the patients can be placed into distinct groups. Then, you’ll create a visualization to share your 
findings with your team and other key stakeholders.

# Process

***Part 1: Prepare the Data***

1. Read data into Pandas DataFrame.

2. Remove 'MYOPIC' column from dataset.

3. Standardize the dataset so that columns that contain larger values do not influence the outcome more than columns with smaller values.

***Part 2: Apply DImensionality Reduction***

1. Perform dimensionality reduction with PCA.

2. Further reduce the dataset dimensions with t-SNE and visually inspect the results.

3. Create a scatter plot of the t-SNE output.

***Part 3: Perform a Cluster Analysis with K-means***

1. Create an elbow plot to identify the best number of clusters.

***Part 4: Make a Recommendation***

1. Based on your findings, write up a brief recommendation for your supervisor. 
