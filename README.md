

# Project Title: Classification of electricity consumers in the Smart Grid system

## Project Overview
In this project, our focus is on leveraging smart meter data within the Smart Grid system. The primary goal is to enhance understanding of electricity consumption behaviors and efficiently classify consumers based on their consumption patterns. This classification is pivotal for enabling flexible demand management and effective energy control.

## Methodology
The project entails implementing unsupervised classification to categorize consumers based on the similarity of their typical electricity consumption behaviors. Our main objective is to group similar observations, facilitating comprehensive data analysis. To achieve this, we utilize the K-means clustering algorithm, which groups consumption behaviors based on attributes into K clusters. The algorithm, readily available in Jupyter libraries, employs Euclidean distances as a measure of similarity between observations.

## Tasks Involved
The project involves several key tasks:
1. **Data Analysis:** Analyzing energy consumption data measured by smart meters.
2. **Tool Installation:** Installing necessary tools such as Anaconda3 and Jupyter Notebook.
3. **Data Acquisition:** Downloading data from the provided source.
4. **Data Preparation:** Preparing the data involves concatenating multiple data files and cleaning defective and irrelevant data.
5. **Parameter Determination:** Determining energy consumption parameters per meter, including total, minimum, maximum, average, average per day of the week, average per weekend day, average per month, average per season, and average per time period.
6. **Classification:** Employing the K-Means algorithm from the scikit-learn library for data classification. This includes determining the optimal number of clusters and visualizing the results of energy consumption parameters by various time periods, days, weekends, and months.

---
