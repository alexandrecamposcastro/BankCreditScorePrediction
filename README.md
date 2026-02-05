# Bank Credit Score Prediction (ML)

A predictive analysis system that classifies bank customers' credit scores based on financial behavior and history. This project implements a classification pipeline using **Python** and **Scikit-Learn**, focusing on data preprocessing and model accuracy comparison.

## Machine Learning Workflow

The project follows a structured data science approach:

1.  **Data Preprocessing:** * Cleaning and handling missing values in the financial dataset.
    * **Label Encoding:** Converting categorical strings (Occupation, Mix of Credit, etc.) into numerical data for model compatibility.
2.  **Feature Selection:** Identifying the most relevant financial indicators for score prediction.
3.  **Model Training:** Implementing and comparing two primary algorithms:
    * **Random Forest Classifier:** For high-accuracy ensemble learning.
    * **K-Nearest Neighbors (KNN):** For distance-based classification.
4.  **Evaluation:** Measuring model performance using accuracy metrics to determine the most reliable predictor for credit risk.

## Tech Stack

* **Language:** Python 3.x
* **Data Manipulation:** Pandas
* **Machine Learning:** Scikit-Learn
* **Model Algorithms:** Random Forest, KNN

## Project Structure

* `main.py` / `analysis.ipynb`: The core script containing the data pipeline and model training.
* `clientes.csv`: The primary dataset containing customer financial history.
* `requirements.txt`: List of dependencies for reproducibility.

## Key Features

* **Categorical Conversion:** Seamlessly transforms raw client data into machine-readable formats.
* **Model Comparison:** Evaluates both Random Forest and KNN to find the best fit for credit analysis.
* **Predictive Power:** Capability to input new client data and receive an instant credit score classification.

## Installation & Usage

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/alexandrecamposcastro/previsao_score_banco.git](https://github.com/alexandrecamposcastro/previsao_score_banco.git)
    ```
2.  **Install dependencies:**
    ```bash
    pip install pandas scikit-learn
    ```
3.  **Run the analysis:**
    ```bash
    python main.py
    ```

## Results
The models are evaluated based on their accuracy scores. In typical financial scenarios like this, the **Random Forest** algorithm usually provides superior results due to its ability to handle complex non-linear relationships in credit data.

---
**Lead Developer:** [Alexandre Campos Castro](https://github.com/alexandrecamposcastro)
