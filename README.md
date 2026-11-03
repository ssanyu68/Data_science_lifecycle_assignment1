Exploratory Data Analysis and Identification of Key Features Influencing Automobile Prices

Overview
This project applies Exploratory Data Analysis (EDA) and statistical techniques to an automobile dataset to identify the key variables associated with vehicle prices.
The analysis explores the dataset, handles missing values, examines distributions, compares automobile prices across different categories, investigates relationships between variables and applies Random Forest feature importance to identify the strongest predictors of automobile prices.
Libraries: Pandas, NumPy, Matplotlib, Seaborn and Scikit-learn

Dataset Description
The project uses the automobileEDA.csv dataset, containing automobile specifications and price information.
The original dataset consists of:
•	201 automobile records.
•	29 variables.
•	Both numerical and categorical features.
Some of the variables include vehicle make, body style, drive-wheel type, engine size, horsepower, curb weight, fuel efficiency and price.

Key Findings
The findings were as follows;
•	Engine size had the strongest positive correlation with automobile price (0.872).
•	Curb weight (0.834) and horsepower (0.810) also had strong positive correlations with price.
•	Highway fuel efficiency had a negative correlation with price (-0.705).
•	Rear-wheel-drive vehicles recorded the highest average price among the drive-wheel categories.
•	Hardtop vehicles recorded the highest average price among the body-style categories.
The Random Forest feature importance analysis identified:

Predictor	Importance score
Engine size	0.6480
Curb weight	0.2008
Highway MPG	0.0505
Width	0.0153
Horsepower	0.0131
Engine size and curb weight were the two most influential predictors in the model, accounting for approximately 84.9% of total feature importance.

Recommendations
Automobile dealers should adopt a data-driven pricing approach supported by predictive modelling. Particular attention should be given to engine size and curb weight when estimating vehicle prices.
Other factors, including fuel efficiency, horsepower, manufacturer, vehicle condition, mileage, customer demand and prevailing market prices which should also be considered.

Limitations
The analysis is based on a relatively small dataset of 201 automobile records. Consequently, the findings may not represent the entire automobile market.
Some vehicle characteristics are related or derived from other variables, which may influence the distribution of feature importance scores. The Random Forest feature importance results indicate predictive usefulness rather than causal relationships.
Additionally, the model was used for exploratory feature ranking and was not independently evaluated on unseen data. Therefore, its feature importance results should not be interpreted as proof of predictive accuracy in real-world pricing.

Repository Contents
The repository contains the following files:
•	Assignment1_Sanyu.ipynb; Executed Jupyter Notebook containing the Python code, analysis, visualisations and interpretations.
•	Sanyu Data.csv; cleaned automobile dataset.
•	README.md – Project overview findings and recommendations.

How to Run the Project
The notebook was developed using Google Colab.
To reproduce the analysis:
1.	Download or clone this repository.
2.	Open Assignment1 Sanyu.ipynb using Google Colab.
3.	Upload the original automobileEDA.csv dataset when prompted by the notebook.
4.	Run the notebook cells sequentially from top to bottom.
5.	Review the outputs, tables, visualisations and interpretations.
6.	Install the required libraries if they are not already available (install pandas numpy, matplotlib and seaborn)
   
Conclusion
This project demonstrates how data exploration, statistical analysis, visualisation and machine learning can be applied to understand automobile pricing patterns. The findings highlight engine size and curb weight as the leading predictors of automobile prices in the analysed dataset. The analysis provides a foundation for more informed, consistent and evidence-based vehicle pricing decisions.

