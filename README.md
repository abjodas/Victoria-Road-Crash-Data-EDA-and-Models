
# Victoria Road Crash Data EDA and Models

## Project Overview

This project analyzes the Victoria Road Crash dataset, performing exploratory data analysis (EDA) and building predictive models to understand and predict accident severity. The analysis aims to identify key factors contributing to road accidents and evaluate the performance of various machine learning models.

## Dataset

The dataset used in this project contains information about road crashes in Victoria, including details such as accident date, location, severity, and other relevant factors. The data is sourced from [Victoria Road Safety Open Data](https://data.vicroads.vic.gov.au/).

## Key Steps in the Analysis

1. **Data Loading and Cleaning**:
    - Load the dataset.
    - Handle missing values and data types.
    - Perform initial data exploration.

2. **Exploratory Data Analysis (EDA)**:
    - Analyze the distribution of key variables.
    - Visualize relationships between features and accident severity.
    - Identify potential patterns and insights.

3. **Feature Engineering**:
    - Create new features based on existing data.
    - Transform and encode categorical variables.

4. **Model Building and Evaluation**:
    - Split the data into training and test sets.
    - Train various machine learning models (e.g., Logistic Regression, Random Forest, etc.).
    - Evaluate model performance using metrics like accuracy, precision, recall, and F1 score.
    - Perform hyperparameter tuning to improve model performance.

5. **Results and Conclusions**:
    - Summarize key findings from the EDA.
    - Discuss the performance of different models.
    - Provide actionable insights and recommendations.

## Dependencies

The following Python packages are required to run the notebook:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- plotly

You can install the required packages using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn plotly
```

## How to Run the Notebook

1. Clone this repository:

```bash
git clone https://github.com/abjodas/Victoria-Road-Crash-Data-EDA-and-Models.git
```

2. Navigate to the project directory:

```bash
cd Victoria-Road-Crash-Data-EDA-and-Models
```

3. Open the Jupyter notebook:

```bash
jupyter notebook VictoriaRoadCrash.ipynb
```

4. Run the cells sequentially to reproduce the analysis.

## Project Structure

- `VictoriaRoadCrash.ipynb`: Jupyter notebook containing the full analysis and modeling.
- `README.md`: Project overview and instructions.
- `data/`: Directory to store the dataset (not included in the repository).

## Results

The final section of the notebook presents the results of the analysis, including visualizations, model performance metrics, and key insights.

## Contributing

Contributions to this project are welcome. Feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License.
