# Child-Mind-Institute-Problematic-Internet-Use-EDA
This notebook performs exploratory data analysis (EDA) and discusses various machine learning approaches for modeling problematic internet use features. The analysis aims to explore different classification and regression techniques to predict outcomes based on the provided dataset.

## Features

- **Exploratory Data Analysis (EDA)**: Data is explored to understand distributions, relationships, and patterns.
- **Machine Learning Approaches**: Multiple approaches are proposed to model the problem, including:
  - Ordinal classification
  - Multiclass classification
  - Regression
  - Custom models with penalization based on distance between categories
- **Data Visualizations**: Visualizations are generated using `matplotlib` and `seaborn` to better understand the data.
  
## Contents

1. **Data Preview**: Loads and previews training, test, and data dictionary datasets.
2. **Machine Learning Problem Setup**: Discusses potential machine learning problems and strategies for solving them.
3. **Exploratory Data Analysis**: The notebook performs a series of visualizations and statistical summaries.

## How to Run

1. Clone the repository and download the notebook.
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. I have provided the link to the dataset in kaggle
4. Run the notebook in a Jupyter environment or Google Colab.

## Dependencies

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `warnings`

## Data Sources

- **train.csv**: Training data for the EDA and model development.[link](https://www.kaggle.com/competitions/child-mind-institute-problematic-internet-use/data?select=train.csv)
- **test.csv**: Test data to validate the models.[link](https://www.kaggle.com/competitions/child-mind-institute-problematic-internet-use/data?select=test.csv)
- **data_dictionary.csv**: Dictionary describing the features of the datasets.[link](https://www.kaggle.com/competitions/child-mind-institute-problematic-internet-use/data?select=data_dictionary.csv)

## Usage

This notebook can be extended for deeper data analysis and model building. Modify the machine learning sections as needed to implement specific classifiers, regressors, or custom models.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
