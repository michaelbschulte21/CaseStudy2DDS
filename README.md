# CaseStudy2DDS
Repository for Case Study 2 for DDS

Zoom Link:
https://smu.zoom.us/rec/share/UicfOpRJ9UpUMYN5WkU0P8bI4tp2Kr0qLPg4Wesb0BpqUJj9UEHzTQAKGK_BlI-M.9eI874DWtKjRxsZJ?startTime=1670804372000

Passcode: 6a^@d&tr

Executive Summary:
  The point of this project was to predict the monthly salary of an employee using linear regression and determining the potential attrition of an employee using k-NN. When completing EDA, there was an emphasis placed on the correlation between the response variables and each response variables' tie to the explanatory variables. The cutoff for the correlation matrix for the salary was +/- 0.1, and the cutoff for attrition was also +/- 0.1. These cutoffs were used to find the initial variables to start with in the model building process. Graphs were made for the salary variable to visualize the correlation and to make sure the relationship was indeed linear. Graphs were made for the attrition relationships, but they proved to be not as useful since the correlation between the variables is quite small.
  The data was split into train and validation sets. The salary MLR model produced an RMSE value of 977.342. This is expected to be lower in the final model which uses all the data provided as the training data. The attrition model has an accuracy of 86.05% with a 95% CI of (72.07%, 94.7%), a sensitivity of 0.9706, and a specificity of 0.4444. It is unknown what the final models yield since the response variables are unknown. However, it is expected the specificity will increase with the increase number of data points that is provided with using the complete data set as the training data.
