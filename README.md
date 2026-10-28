# Smart_Office_Occupancy_Detection

A Python-based machine learning project that predicts whether an office room is occupied based on environmental sensor data (Temperature, Humidity, Light, and CO2 levels) to optimize building energy management.

## 📊 Key Highlights & Results
* **Final Test Accuracy:** **99.3%** using an optimized K-Nearest Neighbors (KNN) classifier (surpassing the client's strict target of 97%).
* **Top Feature Insights:** Exploratory Data Analysis (EDA) proved that **Ambient Light** and **CO2 levels** are the most reliable indicators of human presence.
* **Robust Validation:** Employed **Stratified 5-Fold Cross-Validation** to ensure the model generalizes perfectly to new rooms and floors.

## 🛠️ Tech Stack & Skills
* **Language:** Python
* **Libraries:** Scikit-Learn, Pandas, NumPy, Seaborn, Matplotlib
* **Algorithms Tested:** Logistic Regression, Decision Trees, K-Nearest Neighbors (KNN)
* **Preprocessing:** `StandardScaler` (feature standardization), `GridSearchCV` (hyperparameter optimization)

## ⚙️ How to Run
1. Clone this repository.
2. Install requirements: `pip install ucimlrepo scikit-learn pandas numpy matplotlib seaborn`
3. Run the Jupyter/Colab notebook to execute the pipeline from data collection (via UCI ML repository) to hyperparameter tuning.
