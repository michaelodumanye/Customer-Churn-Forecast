# Customer-Churn-Forecast
Advanced machine learning techniques to forecast customer churn probabilities.

This project aims to predict customer churn in a telecom company using machine learning techniques. Customer churn, also known as customer attrition, refers to the phenomenon where customers stop doing business with a company. By identifying customers who are likely to churn, businesses can take proactive measures to retain them and minimize revenue loss.

## Dataset
The dataset used in this project contains information about telecom customers, including demographic details, services subscribed, tenure, monthly charges, total charges, and churn status. It consists of both numerical and categorical features, making it suitable for exploring various machine learning algorithms.

## Approach
1. **Data Preprocessing**: The dataset underwent preprocessing steps such as handling missing values, encoding categorical variables, and scaling numerical features to prepare it for modeling.
2. **Model Selection**: Several machine learning models were trained and evaluated, including Decision Trees, Logistic Regression, K-Nearest Neighbors, and Random Forest. Hyperparameter tuning was performed using grid search to optimize model performance.
3. **Model Evaluation**: Each model's performance was evaluated using metrics such as accuracy, precision, recall, and F1-score. The Random Forest model emerged as the best-performing model based on these metrics.

## Results
The Random Forest model achieved an accuracy of **80.18%** on the validation dataset, with precision, recall, and F1-score of **67.28%**, **53.09%**, and **59.35%**, respectively. These metrics indicate the model's ability to effectively classify customers into churn and non-churn categories.

## Usage
1. Clone this repository to your local machine.
2. Install the required dependencies listed in `requirements.txt`.
3. Run the provided script or notebook to preprocess the data and train the Random Forest model.
4. Deploy the trained model using containerization for prediction on new data.

## Future Work
1. Explore advanced machine learning techniques such as ensemble methods and neural networks to further improve predictive performance.
2. Incorporate additional features or external data sources to enhance model accuracy and robustness.
3. Continuously monitor and update the model to adapt to changing customer behavior patterns.

## Contributors
- Michael Oko Odumanye

## License
This project is licensed under the MIT License - see the LICENSE file for details.
