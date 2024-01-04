# Overview
This project delves into the realm of crowdfunding, specifically analyzing Kickstarter projects to uncover patterns and trends that lead to a project's success or failure. By employing data science techniques, this project aims to develop a predictive model and clustering analysis to enhance strategic decision-making for creators and the Kickstarter platform.

# Requirements
Before running this project, ensure that you have the following libraries, software, and languages installed:

- Python 
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scipy
- Scikit-Learn
- IPython
- pygwalker (for interactive EDA)
- ydata_profiling (for enhanced EDA)
- kmodes
- tensorflow

# Introduction
Kickstarter has revolutionized crowdfunding by providing a platform for creative, technological, and entrepreneurial projects to secure funding directly from the public. This project leverages data science to analyze various aspects of Kickstarter projects, including financial goals, categories, and timelines, ultimately aiming to optimize project success rates.

# Objective
The primary objective is to utilize data science methodologies to analyze and predict the success or failure of Kickstarter projects. This involves a comprehensive exploratory data analysis, classification of projects, and development of predictive models to aid creators and Kickstarter in making informed decisions.

# Classification Task
- Enhanced Exploratory Data Analysis (EDA) was performed using interactive tools such as pygwalker and ydata_profiling.
- Projects were classified as 'successful' or 'failed' with the aid of TF-IDF Vectorization and various data preprocessing techniques.
- Multiple machine learning algorithms were employed, with the Gradient Boosting Classifier proving to be the most accurate with 75.07% accuracy.

# Clustering
- The project incorporated various features to categorize projects into distinct groups, utilizing algorithms such as KPrototype, KMeans, Hierarchical Clustering, DBSCAN, and Autoencoders.
- A detailed cluster analysis was conducted, identifying four distinct clusters and the characteristics associated with each.

# Recommendations
Based on the insights derived from the analysis, recommendations were provided for both creators and Kickstarter. This includes emphasizing the importance of detailed project descriptions, strategic marketing, active audience engagement, and leveraging data insights for informed project development.

# Acknowledgments
This project was a part of a master's program at McGill. Special thanks to the organizers and contributors who provided the data, tools, and resources necessary to make this challenge a stimulating and enriching experience.
