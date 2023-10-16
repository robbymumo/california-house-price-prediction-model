## California Housing Price Prediction

### Overview

This project focuses on predicting housing prices in California using a dataset obtained from Kaggle. The primary objective is to provide a detailed account of the data preprocessing, feature engineering, exploratory data analysis (EDA), and regression modeling that underpin this predictive analysis.

### Data Source

The dataset used in this project is accessible on Kaggle through the following link: [California Housing Prices Dataset](https://www.kaggle.com/datasets/camnugent/california-housing-prices).

### Dataset Details

The dataset comprises various features related to housing in California. It includes information such as the median housing price, proximity to the ocean, median income, the number of rooms, number of bedrooms, house median age, population, and more.

This diverse set of features makes it an ideal candidate for exploring housing price predictions, as it encompasses both quantitative and categorical attributes.

### Data Preprocessing and Feature Engineering

As a crucial preliminary step, the dataset underwent data preprocessing and feature engineering to ensure it was suitable for predictive modeling. This process involved:

- Addressing missing data: Any missing values within the dataset were handled to ensure data completeness.
- Encoding categorical variables: String columns specifying housing proximity to the ocean, island, bay, or inland were converted into binary options. This transformation allows machine learning models to work more effectively with numeric values.
- Feature scaling: Appropriate scaling was applied to the features to avoid biases in model performance.

### Exploratory Data Analysis (EDA)

Exploratory Data Analysis (EDA) is a crucial aspect of understanding the data and identifying patterns or relationships. In this project:

- EDA included the creation of informative visualizations such as heatmaps to reveal correlations among different features.
- Histograms were used to explore the distribution of values within each feature, helping identify potential outliers and trends.

The EDA process uncovered several key insights, including which features have a significant impact on housing prices. These insights serve as a foundation for subsequent modeling.

### Data Split

For modeling purposes, the dataset was divided into two subsets: the training set and the testing set. This was accomplished using Scikit-Learn's `train_test_split()` method, with an 80-20 split ratio. The training set is used to train the machine learning models, while the testing set is reserved for evaluating model performance.

### Model Comparison

Two regression models were employed for this project:

1. **Linear Regression:** This model is a fundamental choice for regression tasks due to its simplicity and interpretability.
2. **Random Forest Regression:** Random Forest is a more complex ensemble model that combines multiple decision trees to improve predictive accuracy.

### Model Accuracy Scores

To evaluate the performance of the models, accuracy scores were calculated using the test data:

- Linear Regression: Achieved an accuracy score of 0.66117.
- Random Forest Regression: Demonstrated superior performance with an accuracy score of 0.81537.

These scores represent the models' predictive capabilities on unseen data.

### Model Choice and Parameter Tuning

The project revealed that the Random Forest Regression model outperformed the Linear Regression model by a significant margin. This outcome emphasizes the importance of selecting appropriate models for specific tasks.

Additionally, some parameter tuning was applied to the Random Forest model to enhance its predictive accuracy. Fine-tuning parameters can significantly impact model performance.

### Libraries Used

The following Python libraries were utilized in this project:

- NumPy: For efficient numerical operations.
- Matplotlib: For creating data visualizations.
- Scikit-Learn (sklearn): For machine learning tasks.
- Pandas: For data manipulation and analysis.
- Seaborn: For enhancing data visualizations.

Please ensure you have these libraries installed to successfully run the provided code.

### Running the Code

To execute the project code, follow these steps:

1. Ensure you have the required libraries installed in your Python environment.
2. Use Jupyter Notebook to run the provided code. If necessary, adjust file paths or directory structures to match your local setup.

### Results and Discussion

In this section, we delve into the practical implications of the project's findings. We explore the insights generated by the model's predictions regarding housing prices in California, and we discuss how these findings can be valuable for homebuyers, sellers, and real estate professionals.

### Future Work

The project leaves room for further improvements and extensions. Future work may include:

- Exploring additional regression models to assess their suitability for this prediction task.
- Incorporating more features into the analysis to capture additional factors affecting housing prices.
- Refining the existing models through more extensive parameter tuning.


### License

The code and data for this project are shared under the MIT License, allowing for open-source contributions and use. Please refer to the included LICENSE file for more details.

Feel free to reach out with any questions or collaboration opportunities. Your interest and feedback are highly appreciated.
