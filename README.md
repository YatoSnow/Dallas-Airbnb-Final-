# Dallas Airbnb Data Analysis and Price Prediction Project 

This project involves a comprehensive exploratory data analysis (EDA) and machine learning modeling to predict Airbnb accommodation prices in Dallas, Texas.

##  Project Structure

The project follows a structured data science workflow, from data cleaning to final reporting:

1.  **`Dallas_AIRBNB_data_cleaning.ipynb`**
    * **Objective:** Preprocessing and cleaning the raw dataset.
    * **Key Steps:** Handling missing values, fixing data types, and detecting/removing outliers to ensure data quality.

2.  **`Dallas_AIRBNB_WRandEDA.ipynb` (Wrangling & Exploratory Data Analysis)**
    * **Objective:** Visualizing the data to uncover patterns and insights.
    * **Key Steps:** Analyzing price distributions, neighbourhood comparisons, geospatial visualization using `neighbourhoods.geojson`, and examining correlations between variables.

3.  **`Dallas_AIRBNB_modelling.ipynb`**
    * **Objective:** Building and evaluating machine learning models to predict listing prices.
    * **Models Used:** [Insert models here, e.g., Linear Regression, Random Forest, XGBoost]
    * **Evaluation:** Assessing model performance using metrics such as RMSE and R-squared.

4.  **`Dallas_AIRBNB_final report.pdf`**
    * A comprehensive report summarizing the methodology, visual insights, and final conclusions of the study.

5.  **Datasets**
    * `listings.xlsx`: Raw dataset containing Airbnb listings.
    * `neighbourhoods.geojson`: Geospatial data for Dallas neighbourhood boundaries.

##  Technologies & Libraries

The project is developed using **Python**. The following libraries were utilized:

* **Data Manipulation:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn
* **Geospatial Analysis:** Geopandas
* **Machine Learning:** Scikit-learn, [XGBoost/LightGBM if applicable]

##  Key Findings

* **Most Expensive Neighbourhoods:** [Mention top 1-2 expensive areas found in your analysis]
* **Key Price Drivers:** [e.g., Number of bedrooms, location, amenities like pool/gym]
* **Model Performance:** The final model predicts prices with an accuracy of [Insert R2 score or generic accuracy]%.

##  Installation & Usage

To run this project locally:

1.  Clone the repository:
    ```bash
    git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
    ```
2.  Install the required dependencies:
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn geopandas openpyxl
    ```
3.  Run the Jupyter Notebooks in the following order:
    1.  `Dallas_AIRBNB_data_cleaning.ipynb`
    2.  `Dallas_AIRBNB_WRandEDA.ipynb`
    3.  `Dallas_AIRBNB_modelling.ipynb`

---
*Created by **Esref Selvi***
