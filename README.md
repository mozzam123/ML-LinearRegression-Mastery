
# Linear Regression on E-commerce Dataset

This repository contains a Jupyter notebook that demonstrates the application of Linear Regression on an e-commerce dataset. The goal of the analysis is to predict the amount spent by customers on an online clothing store based on various features.

## Dataset Overview

The dataset used in this project is a fictional e-commerce dataset that includes the following features:

- **Email**: Customer's email address.
- **Address**: Customer's physical address.
- **Avatar**: Customer's avatar color.
- **Avg. Session Length**: Average session length of a customer on the website (in minutes).
- **Time on App**: Time spent on the mobile app (in minutes).
- **Time on Website**: Time spent on the website (in minutes).
- **Length of Membership**: Length of membership in years.
- **Yearly Amount Spent**: The amount of money spent by the customer in a year (target variable).

## Project Overview

The project is divided into the following steps:

1. **Data Loading and Exploration**: 
   - Importing necessary libraries such as `pandas`, `matplotlib`, and `seaborn`.
   - Loading the dataset and performing an initial exploration to understand its structure and statistical properties.
   
2. **Data Visualization**:
   - Visualizing the relationships between the features and the target variable using scatter plots and pair plots.
   - Analyzing the correlation between different features.

3. **Model Building**:
   - Splitting the dataset into training and testing sets.
   - Fitting a Linear Regression model to the training data.
   - Evaluating the model's performance using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).

4. **Model Interpretation**:
   - Interpreting the coefficients of the linear model to understand the impact of each feature on the predicted amount spent.
   - Analyzing residuals to assess the model's accuracy.

## How to Use

1. Clone this repository to your local machine.
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```
   
2. Navigate to the project directory.
   ```bash
   cd your-repo-name
   ```

3. Install the required dependencies.
   ```bash
   pip install -r requirements.txt
   ```

4. Run the Jupyter notebook.
   ```bash
   jupyter notebook main.ipynb
   ```

## Dependencies

- Python 3.x
- pandas
- matplotlib
- seaborn
- scikit-learn

You can install these dependencies using `pip`:
```bash
pip install pandas matplotlib seaborn scikit-learn
```

## Contributing

If you have any suggestions or improvements, feel free to submit a pull request or open an issue.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
