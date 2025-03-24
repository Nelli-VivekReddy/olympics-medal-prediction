# olympics-medal-prediction

# Olympic Medal Prediction and Performance Analysis 🏅📊

## Overview
This project analyzes Olympic medal predictions using historical trends and socioeconomic factors. By leveraging machine learning techniques, we aim to forecast Olympic success for countries and understand the key determinants of performance. Additionally, demographic trends in athlete participation—such as age and gender—are explored to gain deeper insights into sports analytics.

## Features
- **Predictive Models**: Develops and compares naive vs. socioeconomic-enhanced models.
- **Exploratory Data Analysis (EDA)**: Visualizes trends in medal distribution, age demographics, and gender participation.
- **Machine Learning Implementation**: Uses regression and classification models for medal prediction.
- **Statistical Insights**: Evaluates the correlation between economic indicators (GDP, population) and Olympic success.

## Technologies Used
- **Programming Language**: Python 🐍
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn 🤖

## Dataset
- **Olympic Performance Data**: Historical medal counts per country.
- **Athlete Demographics**: Age, gender, country, and event participation.
- **Socioeconomic Indicators**: GDP, population, and host nation status.

## Installation & Setup
1. Clone this repository:
   ```sh
   git clone https://github.com/your-username/olympic-medal-prediction.git
   cd olympic-medal-prediction
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the analysis:
   ```sh
   python main.py
   ```

## Usage
1. **Load Data**: Import Olympic datasets for historical performance and demographics.
2. **Preprocess Data**: Clean, normalize, and encode categorical variables.
3. **Train Models**: Train regression models for medal prediction.
4. **Evaluate Performance**: Compare model accuracy using MAE, MSE, and R² scores.
5. **Visualize Insights**: Generate plots for medal trends, gender disparities, and peak athlete ages.

## Model Details
- **Naive Model**: Predicts medals based on historical performance alone.
- **Socioeconomic-Enhanced Model**: Uses GDP, population, and host status for improved accuracy.
- **Machine Learning Algorithms**: K-Nearest Neighbors (KNN), Decision Trees, Bayesian Ridge Regression.

## Results
- **Age-Based Analysis**: Identifies peak performance ages for different sports.
- **Gender Trends**: Shows increasing female participation but persistent performance gaps.
- **Medal Prediction Performance**: Socioeconomic-enhanced models outperform naive models.

## Contributors
- **P. Teja** (22BCS084)
- **M. Karthikeya** (22BCS073)
- **N. Vivek Reddy** (22BCS076)
- **U. Om Pratham** (22BCS133)

## Supervisor
- **Dr. Sunil C. K, Indian Institute of Information Technology Dharwad**

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Olympic dataset sources
- Machine learning research papers on sports analytics
