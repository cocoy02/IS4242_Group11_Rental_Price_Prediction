# IS4242_Group11_Rental_Price_Prediction

## Motivation
A poll showed that most young locals chose to rent instead of purchasing a property due to the lack of savings amidst the soaring prices to buy a property. The rental market has since spiraled out of control as many are facing up to a 70% increase in their rental payments. With the high cost of living in Singapore along with rising rental costs, foreign expats employers in Singapore revealed that employees are facing visible psychological distress and lower work performance due to the unpredictable housing situation. 
Therefore, developing a predictive model to predict rental prices in such difficult circumstances of high demand and constant fluctuations of rental prices would help tenants to make informed decisions and landlords to price their houses at an appropriate price. An emphasis is placed on condominiums which had a steeper increase in rent. Our project aims to come up with a prediction model that incorporates sentiment analysis of reviews. Incorporating reviews as a feature provides valuable information about the location, environment, service and management, investment value of the condominium based on the past experiences of its residents. According to Li and Hitt, reviews reflect the actual quality of the property and thus affects its price. 




## Getting Started
This project mainly uses Jupyter Notebook. Upon cloning this repository into your local machine, run the following command to install all relevant packages.
```bash
pip install -r requirements.txt
```

## Files
The following table contains a brief description of the files and folders in this repository.
| Folder / File | Description |
| - | - |
| **0_Data_Extraction_Property.ipynb** | Property current rental price and related features from SRX |
| **1_Condo Reviews Scraping.ipynb** | Reviews from PropertyGuru to train topic modelling|
| **2_Data Preprocessing.ipynb** | Data cleaning and preprocessing|
| **3_EDA Bivariate Analysis.ipynb** | Exploratory Data Analysis: Bivariate Analysis|
| **3_EDA Geo Analysis.ipynb** | Exploratory Data Analysis: Geographical Analysis |
| **3_EDA Univariate Analysis.ipynb** | Exploratory Data Analysis: Univariate Analysis  |
| **4_Condo Rating.ipynb** | Scrap google reviews for condo and obtain ratings |
| **4_Topic Modelling Accuracy.ipynb** | Topic modelling and performance evaluation|
| **5_Modelling_No_Reviews.ipynb** | Baseline models without features of reviews|
| **5_Modelling_With_Reviews.ipynb** | Improved models with features of reviews|
| **6_Application.ipynb**| Rental price prediction application|
| **Price Data Preprocess.sav** | Fitted Transformer for preprocessing |
| **model_bert_new.pkl**| Fitted model from topic modelling|
| **rf_model_reviews.pkl** | Best model output|
| **Data**| dataset from web scraping and reviews|

## Application
Please run the **6_Application.ipynb** file to input your data and obtain the rental price prediction result. 
