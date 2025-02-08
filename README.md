

### Week 1 summary:

In Week 1 of the project, I performed exploratory data analysis to gain insights into the dataset and prepare it for model development.

 Tasks accomplished :

1)The dataset was loaded, and it was analyzed using methods  .shape, .describe().

2)Check for missing values and duplicates, indicating no missing or duplicate entries.

3)A histogram was plotted to examine the distribution of the target variable, generated_power_kw

**IMPROVEMENTS:**

4)A correlation matrix heatmap was created to find the relationships between features.

5)Highly correlated feature pairs were extracted and printed.



### Week 2 Updates:

Tasks accomplished:

1)Performed Bivariate analysis.

2)Visualized Outliers in the dataset using boxplot.

**IMPROVEMENTS:**

3)Handled the found outlier using IQR method.

4)Visualized Outliers after being treated using boxplot.


### Week 3 Updates:

1)Used Standard scaler to scale all the fearutes to range of 0 to 1 since each of them were different units and ranges.

2)Built a Linear Regression Model to predict target varibale-"generated_power_kw"

3)Evaluated the model by calculating the MAE and r2 scorees from predicitons on both train and test datasets.

**MAE:**


*   Train_score:392.84
*   Test:385.44



**R2 Score:**


*  Train_score:0.70
*   Test_score:0.73


4)Bar plot has been created to visulaise comparsion between train and test data to check for signs of overfitting.

5)A residual plot between actual and predicted values has been to created to visual size how close the model's prediction is.

6)A learning curve has been plotted for the model based on training and testing scores.

