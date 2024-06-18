# Employee Attrition Prediction

## Objectives
The primary goal of this project is to analyze and predict employee attrition within an organization. This involves understanding the various factors that contribute to an employee's termination and developing predictive models to classify the employment status of individuals. The key objectives include:
- Analyzing the factors leading to employee attrition.
- Building predictive models to determine whether an employee is currently active or has been terminated.

## Summary
Employee attrition is a critical issue for organizations as it can lead to increased costs and loss of talent. By leveraging machine learning techniques, we aim to provide insights into the patterns and reasons behind employee turnover. The project utilizes two main machine learning approaches:
- **Decision Trees**: Achieved a classification accuracy of 93% in predicting employee status.
- **Random Forest**: Employed for its enhanced predictive capabilities and robustness over single decision trees.

## Technical Skills
- **R**: Used for data analysis, visualization, and building predictive models.
- **Excel**: Utilized for initial data exploration and manipulation.

## Methodology
1. **Data Collection**: The dataset includes various features such as employee demographics, job roles, satisfaction levels, performance ratings, and other relevant attributes.
2. **Data Preprocessing**: Cleaning and preparing the data for analysis, including handling missing values, encoding categorical variables, and scaling numerical features.
3. **Exploratory Data Analysis (EDA)**: Visualizing and understanding the distribution of data and relationships between variables.
4. **Model Building**: Implementing decision tree and random forest algorithms to build predictive models.
5. **Model Evaluation**: Assessing model performance using metrics such as accuracy, precision, recall, and F1-score.

## Results
- The decision tree model achieved an accuracy of 93%, indicating its effectiveness in predicting employee status.
- The random forest model provided improved predictive performance, leveraging the power of ensemble learning.

## Project Structure
- `data/`: Contains the dataset used for analysis and modeling.
- `scripts/`: Includes the R scripts used for data preprocessing, EDA, and model building.
- `results/`: Stores the results of the analysis and model evaluations.
- `README.md`: Provides an overview and detailed description of the project.
- `requirements.txt`: Lists the dependencies required to run the project (if applicable).

## Usage
To replicate the analysis and results, follow these steps:

1. **Clone the repository**:
    ```sh
    git clone https://github.com/Jonesleo303/Employee-Attrition-Prediction.git
    ```

2. **Navigate to the project directory**:
    ```sh
    cd Employee-Attrition-Prediction
    ```

3. **Install the required dependencies** (if applicable):
    ```sh
    pip install -r requirements.txt
    ```

4. **Run the analysis scripts**:
    Open and run the R scripts in the `scripts/` directory using RStudio or any R environment.

## Conclusion
This project provides a comprehensive approach to understanding and predicting employee attrition using machine learning techniques. The insights gained from this analysis can help organizations develop strategies to reduce turnover and retain valuable talent.

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments
We would like to thank the data providers and the open-source community for their valuable resources and support.
