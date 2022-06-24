## Portfolio

---


### Data Scientist

#### Best Model to Predict Dropout Student

[![](https://img.shields.io/badge/Model-blue?logo=Models)](https://github.com/thinguyen3/student_dropout_prediction/blob/main/src/predict.Rmd) [![](https://img.shields.io/badge/Presentation-red?logo=Presentation)](https://github.com/thinguyen3/student_dropout_prediction/blob/main/doc/ML1_Presentation.pdf) [![](https://img.shields.io/badge/Report-red?logo=Report)](https://github.com/thinguyen3/student_dropout_prediction/blob/main/doc/ML1_Report.pdf) 
[![](https://img.shields.io/badge/View_on_GitHub-green?logo=GitHub)](https://github.com/thinguyen3/student_dropout_prediction)

In this project, I presented a case study on automatically detecting whether a student is at-risk of dropout at New Jersey City University using R and R Markdown report.

Models: Bagging, Stacking with Random Forest, Classification Tree, Logistic Regression, and SVM.

These models achieve high predictive power, combining values of AUC ROC for decision-making with capable of achieving with accuracy score of over 96% in its predictions. 

![ROC Curves plot](/images/ROCcurves.png "ROC Curves plot")

---
#### Data Visualization using d3

##### U.S Flight Delay Dashboard

[![](https://img.shields.io/badge/Presentation-red?logo=Presentation)](https://github.com/thinguyen3/d3_proj/blob/main/d3_presentation.pdf) 
[![](https://img.shields.io/badge/View_on_GitHub-green?logo=GitHub)](https://github.com/thinguyen3/d3_proj) [![](https://img.shields.io/badge/JavaScript-F7DF1E?logo=JavaScript)](https://github.com/thinguyen3/d3_proj/tree/main/scripts) [![](https://img.shields.io/badge/HTML-E34F26?logo=HTML)](https://github.com/thinguyen3/d3_proj/blob/main/d3.html)

The goal of this project is to take a look inside into the U.S flight delay data by using many various visualizations such as chart, donut, force, choropleth map to answer these questions: how does the total number of flight delay change, which airport has the most flight delay, the relationship between origin and destination airports.

Technology: HTML5, CSS6, JavaScript, and d3.

Figure 1: Bar chart and Donut chart showing Flight Delay, Total Flight, and Flight Delay within the Airlines

![barchart](/images/barchart.png "Bar Chart")

Figure 2: Force Layout Graph showing the flight delay from the origin and the destination between the top 20 airports

![graph](/images/ForceLayoutGraph.png "Graph")

Figure 3: Choropleth map showing the flight delay in the U.S. States

![ChoroplethMap](/images/ChoroplethMap.png "Map")

---

#### Best Model to Predict Car License Plate Detection

[![](https://img.shields.io/badge/Run_in_Google_Colab-EE4C2C?logo=GoogleColab)](https://drive.google.com/file/d/1TWdll3VPMMg90qZxWiJrsrIdRUT5AUH9/view?usp=sharing) [![](https://img.shields.io/badge/Model-blue?logo=Models)](https://github.com/thinguyen3/car_license_plate_detection/blob/main/scripts/ThiNguyen_FInalProject_ML2%20submit.ipynb) [![](https://img.shields.io/badge/View_on_GitHub-green?logo=GitHub)](https://github.com/thinguyen3/car_license_plate_detection) 

The target of this project is to identify vehicles by detecting and recognizing their license plates. Results can be used for vehicle tracking and vehicle activity analysis.

I trained various neural networks from pre-trained CNNs (Resnet50, VGG16, VGG19) with different architectures, and hyperparameters. VGG16 models showed the best accuracy score with 84% recognition rate.

![Scores_Plot](/images/plot.png "Scores Plot")

How model localize license plates on the testing set

![Car_Plot](/images/car.png "Car Plot")

---

#### Best Model to Predict On-time Shipment with Machine Learning

[![](https://img.shields.io/badge/Run_in_Google_Colab-EE4C2C?logo=GoogleColab)](https://colab.research.google.com/drive/1bxXKo5suz7yBmiH2ol0DJPokOOjafoz5)
 [![](https://img.shields.io/badge/Model-blue?logo=Models)](https://github.com/thinguyen3/Predicting-on-time-shipment-with-Machine-Learning/blob/main/Google%20Colab.ipynb) [![](https://img.shields.io/badge/Presentation-red?logo=Presentation)](https://github.com/thinguyen3/Predicting-on-time-shipment-with-Machine-Learning/blob/main/Presentation.pdf) [![](https://img.shields.io/badge/Report-red?logo=Report)](https://github.com/thinguyen3/Predicting-on-time-shipment-with-Machine-Learning/blob/main/Report.pdf) [![](https://img.shields.io/badge/View_on_GitHub-green?logo=GitHub)](https://github.com/thinguyen3/Predicting-on-time-shipment-with-Machine-Learning) 

This research project focused on how to apply Machine Learning to make predictions regarding shipping on time, from an international e-commerce company to their customers. Using logistic regression and train/testing method with building three models to predict the shipping, we want to discover key insights from which factors significantly affect ‘Reached on time’ and predict whether a product will be delivered on time or not.


Models: Logistic Regression, Decision Tree, SVM.

Heatmap of feature (and outcome) correlations

![correlations](/images/corr.png)

![regression](/images/regression.png)

![Coef](/images/coef.png)

#### Model selection

|          Model	    |Accuracy Score	|Type I error|
|---------------------|---------------|------------|
|Logistic Regression	|64%	          |454         |
|Decision Tree	      |68%	          |65          |
|SVM	                |64%	          |333         |

The results show that Cost of the product, Prior purchases, Discount offered, Weight in gram and Product important function have a significant influence on the model, especially Cost of the product and Prior purchases. Cost of the product has a negative influence on the prediction, higher Cost of the product is correlated with a not on time shipment, higher on Cost of the product, less on not on time shipment. 

### Data Analyst

#### BAC & CITI Financial Valuation

1. Purpose of valuation: The purpose of this valuation is to know the values of two companies selected by investors in order to determine the economic value of the company as it is an informed estimate of the total worth of a company and helps us to know which company has better performance.

2. Benefits of bsiness valuation: The valuation helps us to know the wealth of a company. Knowing what an asset is worth and what determines that value is a pre-requisite for intelligent decision making and in choosing investments for a portfolio in deciding on the appropriate price to pay or receive in a takeover and in making investment, financing, and dividend choices when running a business.

3. Data Sources:

|         Material          |     Source    |
|---------------------------|---------------|
|BAC Financial Statement	   |https://www.sec.gov/cgi-bin/viewer?action=view&cik=70858&accession_number=0000070858-21-000023&xbrl_type=v#|
|CITI Financial Statement   |https://www.sec.gov/cgi-bin/viewer?action=view&cik=831001&accession_number=0000831001-21-000042&xbrl_type=v#      
|BAC historical Price       |https://finance.yahoo.com/quote/BAC/history?p=BAC
|CITI historical Price      |https://finance.yahoo.com/quote/C/history?p=C
|SPY                        |https://finance.yahoo.com/quote/SPY/history?p=SPY

4. Valuation Methods Categories:

Absolute valuation models:

It helps to find the true value of an investment based only on fundamentals, which includes dividends, cash flow, and growth rate for a single company only. Some methods under this category are:

• DCF( Discounted Cash Flow method)

• Asset-based model

• Dividend discount Model

Relative valuation models:

• P/E (price to earning) ratio used for stock valuation

• E V/sales (enterprise value to sales ratio)

• Price to book ratio

Methods Used (Absolute Valuation Models):

• Discounted Cash Flow (DCF): (Enterprise value approach)

BAC:

![BAC_DCF](/images/BAC_DCF.png "BAC DCF")

CITI:

![CITI_DCF](/images/BAC_DCF.png "CITI DCF")

• Weighted Average Cost of Capital (WACC)

![WACC](/images/WACC.png "WACC")

Balance statement for calculation of net debt

BAC: 

![BAC_Balance](/images/BAC_Balance.png "BAC_Balance Statement")

CITI:

![CITIBalance](/images/CITI_Balance.png "CITI_Balance Statement")

5. Invesment decision:

As we are looking for less risk, so will opt for DCF  valuation, according to which BAC has all  positive projected cash flows along with EV. So, If I   invest on BAC in 2019, can still continue in 2020.


#### Project on Employee Database Management System

[![](https://img.shields.io/badge/Presentation-red?logo=Presentation)](https://github.com/thinguyen3/employee_database_management/blob/main/docs/Presentation.pdf) [![](https://img.shields.io/badge/Report-red?logo=Report)](https://github.com/thinguyen3/employee_database_management/blob/main/docs/Employee%20Database%20Management%20System.pdf) 

Objective is to set up an employee information system with data such as the status of employees, departments, leave, salary.

Collected entities, tables, and data types, and designed a relational database to store the data.

![Relational_Database](/images/ERD.png "ERD")

---

### Financial Technology

#### P2P Flatform for SMEs Project

[![](https://img.shields.io/badge/Presentation-red?logo=Presentation)](https://github.com/thinguyen3/thinguyen3.github.io/blob/main/pdf/ProLendingPresentation.pdf)

![p2p](/images/p2p.png)

In this project we have observed and analyzed competitors to identify potential issues in the market to launch our service named ProLending that is an easy-to-use peer to peer platform offering competitive rates and a wider range of loan options for small businesses.

Our platform’s goal is to build strong relationships with our product users by offering loans from $1,000 to $250,000 for MSME’s and SME’s.

---
<p style="font-size:11px">Page template forked from <a href="https://github.com/evanca/quick-portfolio">evanca</a></p>
<!-- Remove above link if you don't want to attibute -->
