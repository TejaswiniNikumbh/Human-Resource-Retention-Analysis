# Human-Resource-Retention-Analysis
In this project, I developed a machine learning model to predict employee attrition. I started by exploring and understanding the dataset, getting insights into the different features and their distributions. After that, I preprocessed the data, handling missing values, encoding categorical variables, and performing feature scaling.</br>

To predict employee attrition, I implemented two machine learning algorithms: logistic regression and random forest classifier. I trained these models using the preprocessed data and evaluated their performance using various metrics such as accuracy, confusion matrix, and classification report.</br>
###EDA Steps
Explored the dataset to understand its structure and variables present.</br>
Calculated summary statistics for numerical variables to assess distribution and range.</br>
Created visualizations such as histograms, bar charts, and box plots to analyze data patterns and relationships.</br>
Addressed missing values by deciding whether to impute or remove them.</br>
Analyzed frequency distributions and created bar plots for categorical variables.</br>
Conducted correlation analysis to identify significant relationships among features.</br>
Some graphs for insights:
![image](https://github.com/TejaswiniNikumbh/Human-Resource-Retention-Analysis/assets/92621668/260c2669-4036-4e2d-aee0-2cbcd5ca0c7c)

![image](https://github.com/TejaswiniNikumbh/Human-Resource-Retention-Analysis/assets/92621668/dc90f1f0-09eb-400f-a86c-5b8fc88c8e99)
![image](https://github.com/TejaswiniNikumbh/Human-Resource-Retention-Analysis/assets/92621668/ea130fff-56b7-4e4a-87a8-422c72641f49)

The logistic regression model achieved an accuracy of 76.69%. It correctly predicted 3161 instances of employees who stayed and 290 instances of employees who left. However, it struggled to accurately identify employees at risk of attrition, as indicated by its lower recall and f1-score for the class representing employees who left.

On the other hand, the random forest classifier outperformed logistic regression with an impressive accuracy of 98.56%. It correctly predicted 3419 instances of employees who stayed and 1016 instances of employees who left. The model demonstrated high precision, recall, and f1-score for both classes, showcasing its effectiveness in identifying employees likely to leave the company.

Overall, this project highlights the application of machine learning techniques in predicting employee attrition. The results emphasize the potential of the random forest classifier as a robust model for identifying employees at risk of leaving, which can be valuable for organizations in managing and mitigating attrition.
