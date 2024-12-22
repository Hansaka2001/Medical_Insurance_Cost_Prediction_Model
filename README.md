# Medical Insurance Cost Prediction Model

This project aims to predict the medical insurance costs for individuals based on various factors such as age, gender, BMI, number of children, alcohol habits, and region of residence. By leveraging a dataset of historical medical cost records, the model applies data preprocessing techniques and exploratory data analysis (EDA) to uncover patterns in the data.

The final predictive model uses machine learning algorithms to estimate insurance costs accurately. This solution can be utilized to assist insurance companies in risk assessment and policy pricing while providing valuable insights for healthcare analytics.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Data](#data)
- [Model](#model)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/Hansaka2001/Medical_Insurance_Cost_Prediction_Model.git
    cd Medical_Insurance_Cost_Prediction_Model
    ```

2. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Open the Jupyter Notebook:
    ```sh
    jupyter notebook model.ipynb
    ```

2. Run the cells in the notebook to preprocess the data, train the model, and evaluate the results.

## Project Structure

- [model.ipynb](http://_vscodecontentref_/0): Jupyter Notebook containing the code for data preprocessing, model training, and evaluation.
- [medical_cost.csv](http://_vscodecontentref_/1): Dataset used for training and evaluating the model.
- [.gitignore](http://_vscodecontentref_/2): Specifies files and directories to be ignored by Git.
- [README.md](http://_vscodecontentref_/3): Project documentation.

## Data

The dataset [medical_cost.csv](http://_vscodecontentref_/4) contains the following columns:
- `age`: Age of the individual.
- `gender`: Gender of the individual(male/female).
- `bmi`: Body Mass Index of the individual.
- `children`: Number of children covered by the insurance.
- `alcohol`: Whether the individual consumes alcohol(yes/no).
- `region`: Region of residence.
- `charges`: Medical insurance cost.

## Model

The model uses various machine learning algorithms to predict the insurance costs. The following steps are performed in the notebook:
1. Data Preprocessing: Handling missing values, encoding categorical variables, and scaling numerical features.
2. Exploratory Data Analysis (EDA): Visualizing the data to understand the distribution and relationships between variables.
3. Model Training: Training different machine learning models and selecting the best one based on performance metrics.
4. Model Evaluation: Evaluating the model using metrics such as Mean Squared Error (MSE) and R-squared.

## Results

The results of the model are evaluated and visualized in the notebook. Key findings and insights are documented to help understand the model's performance and potential improvements.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the LICENSE file for details.