# Data Science Salary Prediction AI Integrated

This repository contains the code and data for a comprehensive data science salary prediction project. The project includes data processing, model training, evaluation, and deployment using Streamlit. Below is a detailed description of each file and its purpose.

## Repository Contents

### 1. Final_streamlit_code.ipynb
- **Description:** This Jupyter notebook contains the final code for deploying the salary prediction model using Streamlit. It demonstrates how to build an interactive web application that allows users to input features and receive predicted salary outcomes in real-time. The notebook covers the setup of the Streamlit app, integration with the trained model, and the creation of a user-friendly interface.

### 2. best_rf_model.pkl
- **Description:** This file contains the best performing random forest model, serialized as a pickle file. It is the result of extensive hyperparameter tuning and cross-validation to ensure high prediction accuracy. The model is used in the Streamlit app to make real-time salary predictions based on user input.

### 3. data-science-salary-prediction-ai-integrated.ipynb
- **Description:** This is a comprehensive Kaggle notebook that includes the entire workflow for the data science salary prediction project. It covers data exploration, preprocessing, feature engineering, model training, and evaluation. The notebook provides insights into the methodologies used to clean and prepare the data, as well as the rationale behind the chosen algorithms and hyperparameters.

### 4. data_with_predictions.csv
- **Description:** This CSV file contains the final dataset with salary predictions appended. It includes both the original features and the predicted salaries, allowing for further analysis and validation of the model's performance. This dataset can be used to compare predicted values with actual salaries or to visualize the prediction results.

### 5. glassdoor_jobs.csv
- **Description:** This CSV file contains the raw data used in the project, sourced from Glassdoor. It includes job listings with various features such as job title, company, location, and estimated salaries. The raw data serves as the foundation for all preprocessing and modeling steps, making it crucial for understanding the initial data structure and quality.

## Repository Files Navigation

- **Final_streamlit_code.ipynb:** Navigate to this notebook to see the complete code for deploying the model using Streamlit.
- **best_rf_model.pkl:** Load this file to utilize the trained random forest model for salary predictions.
- **data-science-salary-prediction-ai-integrated.ipynb:** Explore this notebook to understand the full project workflow, from data acquisition to model evaluation.
- **data_with_predictions.csv:** Check this file to view the final dataset with salary predictions included.
- **glassdoor_jobs.csv:** Review the raw data file to understand the initial dataset used for training and testing the models.

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/data-science-salary-prediction.git
   cd data-science-salary-prediction
   ```

2. **Install the required dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Streamlit app:**
   ```bash
   streamlit run Final_streamlit_code.ipynb
   ```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- The dataset was sourced from Glassdoor.
- The Kaggle notebook served as a basis for data exploration and model training.

For any issues or contributions, please feel free to create an issue or a pull request.
