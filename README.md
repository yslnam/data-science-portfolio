# Data Science Portfolio
A repository containing data science projects completed by me for school, self-taught purposes, and/or fun.

* Languages: Python, R
* Format: iPython, R Markdown, R Shiny Server and UI
* Demonstrated skills: Extraction, Cleaning, Wrangling, Processing, Analysis, Modeling, Visualization
* Specialities: Web Scraping, Machine Learning

## Directory Structure
```
├── README.md           <- Top-level README
│
├── data                <- All tasks for unstructured and structured data types
│   ├── extraction      <- Unstructured data extraction, e.g. web scraping
│   ├── cleaning 	<- Raw, structured data cleaning and wrangling
│   ├── processing    	<- Structured data preprocessing and processing
│   ├── analysis    	<- Structured data analysis
│
├── modeling           	<- Trained and tested regression, machine learning, and NLP models
│
├── visualizations      <- Data visualization and reporting
│                                           
├── .gitignore          <- Avoids uploading data, credentials, outputs, system files etc
```

## Projects
1. Macro Risk Index
2. Trends in TED Talks on Global Issues, Science, and Technology
3. Valuating Houses in Ames, Iowa Using Predictive Modeling
4. Identifying Underserved Populations as CitiBike Customers

## Contents
- ### Data Extraction
	- __Web Scraping__
		- [Scraping TED Talks](https://github.com/yslnam/data-science-portfolio/tree/master/data/extraction/scraping-ted-talks): Scraped and parsed unstructured data from TED Talks using Selenium (Python) to identify trends in global issues, science, and technology. (See next: "[Cleaned Scraped TED Talks]()")
		
	_Libraries/Packages: Selenium_ 
	
- ### Data Cleaning, Wrangling, and Processing
	- __Python__
		- [Encoding Categorical Features for Predictive Modeling of Ames Housing Prices](https://github.com/yslnam/data-science-portfolio/tree/master/data/processing/predict-ames-housing-prices): Cleaned, wrangled, and preprocessed Ames, Iowa housing price data for predictive modeling. (See next: "[Predicting Housing Prices in Ames, Iowa](https://github.com/yslnam/data-science-portfolio/tree/master/modeling/ML/predict-ames-housing-prices)")
		
		- [Feature Engineering CitiBike Data](https://github.com/yslnam/data-science-portfolio/tree/master/data/processing/citibike-data): Cleaned, wrangled, and processed CitiBike data by merging or adding new features for data analysis. (See next: "[Exploring Feature Engineered CitiBike Data]()")
		
	_Libraries/Packages: NumPy, Pandas, Pandas API, datetime, PyProj, category_encoders (including CatBoost)_ 

	- __R__ 
		- [Cleaning Scraped TED Talks](https://github.com/yslnam/data-science-portfolio/tree/master/data/cleaning/scraping-ted-talks): Cleaned and wrangled scraped data from TED Talks. (See previously: "[Scraping TED Talks](https://github.com/yslnam/data-science-portfolio/tree/master/data/extraction/scraping-ted-talks)"; See next: "[Measuring Trendiness of TED Talks]()")
		
	_Libraries/Packages: tidyverse, lubridate, janitor_ 		

- ### Data Analysis
	- __Python__
		- [Exploring Feature Engineered CitiBike Data](https://github.com/yslnam/data-science-portfolio/tree/master/data/analysis/citibike-data): Conducted exploratory data analysis of feature engineered CitiBike Data. Identified user, geographic, and station usage, and net inflow/outflow patterns in CitiBike rides in order to identify underserved population. (See previously: "[Feature Engineering CitiBike Data](https://github.com/yslnam/data-science-portfolio/tree/master/data/processing/citibike-data)"; See next: "[Visualizing Patterns in CitiBike Rides]()")
		
	_Libraries/Packages: NumPy, Pandas, Pandas API, datetime, Seaborn, Matplotlib, Plotly_ 

	- __R__ 
		- [Exploring Conflict Risk Indicators](https://github.com/yslnam/data-science-portfolio/tree/master/visualization/risk-index): Created a "quick and dirty" exploratory data analysis dashboard and interactive tool. Developed a Shiny app to compile all interactive visualizations. (See next: "[Globally Mapping Conflict Risk Indicators](https://github.com/yslnam/data-science-portfolio/tree/master/visualization/risk-index)")
	
		- [Measuring "Trendiness" of TED Talks](): Constructed multivariate and composite indicators to measure “trendiness” of global issues, science, and technology TED Talks. (See previously: "[Cleaning Scraped TED Talks]()"; See next: "[Visualizing Trends in TED Talks]()")
	
	_Libraries/Packages: tidyverse, tidyr, lubridate, Shiny, shinydashboard, shinythemes, rgdal, leaflet, sp, RColorBrewer, reshape2_  

- ### Modeling
	- __Machine Learning__
		- [Predicting Housing Prices in Ames, Iowa](https://github.com/yslnam/data-science-portfolio/tree/master/modeling/ML/predict-ames-housing-prices): Modeled and predicted housing prices in Ames, Iowa using Lasso Regression, ElasticNet Regression, Ridge Regression, Random Forest, and XGBoost (Gradient Boosting). Collaborated with teammates, with each member responsible for a model. Primarily responsible for Random Forest. (See previously: "[Encoding Categorical Features for Predictive Modeling of Ames Housing Prices](https://github.com/yslnam/data-science-portfolio/tree/master/data/processing/predict-ames-housing-prices)"; See next: "[Valuating Houses in Ames, Iowa]()")
		
	 _Libraries/Packages: scikit-learn_ 

- ### Data Visualization
	- __Python__
		- [Valuating Houses in Ames, Iowa](): Selected key features in predictive random forest modeling for housing prices in Ames, Iowa. Used "black box" deconstruction techniques to interpret random forest model and results. (See previously: "[Predicting Housing Prices in Ames, Iowa](https://github.com/yslnam/data-science-portfolio/tree/master/modeling/ML/predict-ames-housing-prices)")
	
		- [Visualizing Patterns in CitiBike Rides](): Visualized user, geographic, and station usage patterns in CitiBike rides from feature engineered data. 
		
	_Libraries/Packages: Pandas, NumPy, Seaborn, Matplotlib, scikit-learn, pprint, rfpimp, treeinterpreter_ 

	- __R__ 
		- [Globally Mapping Conflict Risk Indicators](https://github.com/yslnam/data-science-portfolio/tree/master/visualization/risk-index): Created an interactive map of conflict risk indicators by country using leaflet. Developed a Shiny app to compile all interactive visualizations. (See previously: "[Exploring Conflict Risk Indicators](https://github.com/yslnam/data-science-portfolio/tree/master/visualization/risk-index)")
		
		- [Visualizing Trends in TED Talks](): Visualized trends in global issues, science, and technology TED Talks using self-constructed multivariate and composite indicators. (See previously: "[User Sentiment on TED Talk Trends]()")
		
  	_Libraries/Packages: tidyverse, scales, paletteer, ggally, hrbrthemes, Shiny, shinydashboard, shinythemes, rgdal, leaflet, sp, RColorBrewer, reshape2_ 
