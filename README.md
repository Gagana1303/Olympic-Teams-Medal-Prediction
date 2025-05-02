# Olympic-Teams-Medal-Prediction
This project analyzes Olympic teams performance data using machine learning. The primary goal is to understand the relationship between features like the number of athletes, average age, and previous medals with the number of medals won. The project uses a linear regression model to predict medal counts based on historical data. The analysis includes data cleaning, visualization, correlation analysis, and model evaluation using mean absolute error.

## Overview
This project predicts the number of medals Olympic teams might win based on historical data. The dataset contains information such as the team name, country, year, number of athletes, average age, previous medal count, and actual medals won.

## Dataset
- teams.csv: Contains team-level data from past Olympic events.
- Features include:
   team: Team name
   country: Country code
   year: Olympic year
   athletes: Number of athletes
   age: Average age of athletes
   prev_medals: Previous medal count
   medals: Medals won in the current year

## Tools and Libraries
- Python
- pandas
- seaborn
- scikit-learn
- NumPy

## Methodology
1. Data Cleaning
   - Removed rows with missing values in key columns.
2. Visualization
   - Explored correlation between variables.
   - Visualized relationships with lmplot and histograms.
3. Modeling
   - Split data into training (before 2012) and testing (2012 and after).
   - Built a linear regression model using athletes and prev_medals as predictors.
   - Evaluated model using Mean Absolute Error (MAE).

##  How to Use

1. Clone the repository:
   bash
   git clone https://github.com/Gagana1303/Olympic-Teams-Medal-Prediction.git
   cd Olympic-Teams-Medal-Prediction
2. Install dependencies:
   pip install -r requirements.txt
3. Run the Jupyter Notebook:
   jupyter notebook olympic medal.ipynb


## Results
 - The model showed a strong correlation between the number of athletes and previous medals with current medal count.
 - MAE was used to quantify prediction error on the test set.

## Conclusion
Using basic machine learning techniques and historical data, we can reasonably estimate the number of medals a team might win. While this model is simple, it highlights the value of previous success and team size in Olympic performance. Further enhancements could include more complex models and additional features like sport type or funding data.

## Contact
Gagana M R
Email: gaganamr710@gmail.com
LinkedIn: linkedin.com/in/gagana-m-r-3bb0172a4

#machinelearning #Olymic #medalprediction #datascience #python #scikitlearn
