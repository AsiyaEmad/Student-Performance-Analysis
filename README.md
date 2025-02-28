# Student-Performance-Analysis

## Overview
This project focuses on analyzing student performance data through exploratory data analysis (EDA). It aims to identify key patterns and correlations that impact academic success, using data visualization and statistical methods.

## Dataset
The analysis is performed on the `Students_Grading_Dataset.csv`, which includes various student-related attributes such as study hours, attendance, stress levels, and scores.

## Objectives
- Identify missing and duplicate values.
- Generate summary statistics.
- Detect and handle outliers.
- Clean and preprocess data.
- Perform feature engineering and normalization.
- Visualize key patterns in student performance.
- Conduct correlation analysis.

## Key Features
- **Data Cleaning**: Handling missing values and removing unnecessary columns.
- **Outlier Detection**: Using boxplots and IQR method to detect outliers.
- **Feature Engineering**: Standardizing numerical features and creating derived variables such as Engagement Score.
- **Data Visualization**:
  - Histograms for study hours, sleep hours, and stress levels.
  - Pie charts for family income level and extracurricular activities.
  - Scatter plots for attendance vs. final score and study hours vs. total score.
  - Correlation heatmaps.
- **Interactive Dashboard**: Built using Dash to explore key insights dynamically.

## Technologies Used
- **Python Libraries**:
  - `pandas`, `numpy` - Data manipulation and analysis
  - `matplotlib`, `seaborn`, `plotly` - Data visualization
  - `sklearn.preprocessing` - Data normalization
  - `dash` - Interactive dashboard creation

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/student-performance-analysis.git
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook to perform EDA.
4. Launch the interactive dashboard (if applicable).

## Results & Insights
- Students who study more hours tend to have higher total scores.
- Sleep hours show a moderate relationship with stress levels.
- Attendance percentage has a weak correlation with academic performance.
- Family income level does not significantly impact student grades.

## Contributing
If you would like to contribute, feel free to fork the repository and submit a pull request.

## License
This project is open-source and available under the MIT License.

