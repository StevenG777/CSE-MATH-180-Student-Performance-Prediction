# CSE-MATH-180-Student-Performance-Prediction
## Descriptions:
The project aimed to investigate the significant socio-economic factors contributing to affecting student performance in school. We decided to use feature selection to identify important features and predict the students' performance with several machine-learning models.

## Project Details:
- Performed exploratory data analysis techniques like visualizing the descriptive statistics and data distribution through box and bar plots
- Pre-processed the data through one-hot encoding for categorical values and data cleansing
- Utilized subset selection methods and K-fold cross-validation to determine the significant features
- Applied various models such as linear regression, random forest, cubic spline, Multilayer Perceptron
- Tuned the hyperparameters of the Multilayer Perceptron model to enhance prediction ability leading to an 8.5% decrease in test errors

## File Details:
- [Project.Rmd](https://github.com/StevenG777/UCM-MATH180-Student-Performance-Prediction/blob/main/Project.Rmd): Source code file
- [Project.html](https://github.com/StevenG777/UCM-MATH180-Student-Performance-Prediction/blob/main/Project.html): HTML rendered file for the source code
- [MATH 180 Report.pdf](https://github.com/StevenG777/UCM-MATH180-Student-Performance-Prediction/blob/main/MATH%20180%20Report.pdf): Detailed report for the project
- [MATH.csv](https://github.com/StevenG777/UCM-MATH180-Student-Performance-Prediction/blob/main/Math.csv): Dataset file

## Results:
- Failures and Absence are the significant factors to enhance the performance of the model. However, none of them were socio-economic factors. We concluded that the socio-economics perspective of students were not significant in predicting the student’s performance
- Random forests model led in minimizing error differences ranging from 0-36.7%
- Utilized cross-validation to prune decision trees, select spline’s degrees of freedom, and tune hyperparameters resulting in an 8.5% decrease in test errors

## Reference
Kaggle dataset source: [Link](https://www.kaggle.com/datasets/whenamancodes/student-performance)
