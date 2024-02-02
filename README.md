[notebook file](https://github.com/sarah10001/Paris_Phase_2_Project/blob/main/Housing%20Prediction%20Model.ipynb)
[Presentation slides](https://www.canva.com/design/DAF7hB_5voU/Qdle8P-0QeZ-RsJfIVmDwg/edit)
# Paris Housing Project 

## Overview
### Problem Statement

Over the years, Paris has grappled with various housing issues, ranging from affordability and supply and demand imbalances to rising rent prices and regulatory challenges. The city faces urbanization challenges, social housing shortages, and market speculation, and is impacted by external events. In response to these challenges, a distinguished group of investors is establishing a real estate firm in Paris focusing on addressing the critical issue of affordable housing.

### Project Objectives

The investors have engaged Mali Safi and Sons to analyze existing data, draw meaningful insights, and guide their strategic decisions toward providing affordable housing solutions. The key objectives of the project are:

  . Identify Variables Affecting Prices: Understand the factors that influence property prices in the     Paris real estate market.

  . Construct Regression Model: Build a regression model that correlates property prices with             relevant variables, providing a predictive tool for pricing.

  . Evaluate Model Performance: Assess the performance of the regression model in identifying and         quantifying the factors that significantly affect property prices.

### Key Challenges

The real estate company aims to navigate challenges posed by a burgeoning urban population and evolving socio-economic dynamics, ensuring that the housing solutions provided are affordable and align with the Parisian population's diverse needs.

By achieving these objectives, the investors hope to make informed decisions that contribute to the development of sustainable and affordable housing solutions in Paris.

## Business Understanding:
### Stakeholders

Sakura real estate firm from Japan: They seek to venture into the real estate market in Paris

## Data Understanding and Analysis

### Source of Data
The dataset used in this analysis is ParisHousing.csv, acquired from kaggle datasets.

The data frame has 10000 rows and 17 columns.

### Description of Data
The variables in the data are squareMetres, numberOfRooms, hasYard, hasPool, floors, cityCode, cityPartRange, numPrevOwners,	made,	isNewBuilt,	hasStormProtector,	basement,	attic,	garage,	hasStorageRoom,	hasGuestRoom	and price. 
For modeling purposes, cityCode and cityPartRange were dropped due to a mismatch between town codes and the town names.
The variables were further categorized into 2 classes, dependent variables and independent variables.
  
  Dependent variable:
   
    .Price
  
  Independent variable:
    
    . Square meters
    . No of rooms
    . Has pool
    . Has yard
    . Year made
    . Is new built
    . Has storm protector
    . Basement
    . Attic
    . Garage
    . Storage room
    . Guest room
  
### Visualizations



# 1. Heatmap of variable relationships
![Screenshot 2024-02-01 095110](https://github.com/sarah10001/Paris_Phase_2_Project/assets/141912187/3f5b23c4-690d-4714-8569-01dfdf6e1217)


# 2. Correlation with Price
![Screenshot 2024-02-01 095204](https://github.com/sarah10001/Paris_Phase_2_Project/assets/141912187/824cd82f-8739-4514-bb28-e7c572c367df)


# 3. Predicted Regression Line
![Screenshot 2024-02-01 095258](https://github.com/sarah10001/Paris_Phase_2_Project/assets/141912187/4d669d23-2235-4dc3-b4d4-0464bba8af26)


### Summary 
The comprehensive analysis conducted by Mali Safi and Sons serves as a pivotal guide for the Distinguished Group of Parisian Investors venturing into the real estate sector. The significance of the models lies in their ability to offer nuanced insights, predictive accuracy, and strategic guidance tailored to the unique dynamics of the Paris housing market.

In culmination with the formulated hypothesis that intrinsically correlates to the models created and clear insight that influences the clear decision-making process of the Distinguished group Investors.

The models, developed through meticulous data analysis, not only identify key variables i.e ('numberOfRooms', 'basement','attic', 'garage') influencing property prices but also providing a robust framework for predictive modeling. These tools enable Mali Safi and Sons to offer valuable guidance to the investors, informing their decisions on strategic investments, risk mitigation, and the development of tailored solutions to address the pressing issue of affordable housing.

By delving into the relationships between various features and property prices, e.g. take a look at the price for a house with 83841sqmeters which is 8390030.5. The models empower the investors to navigate the intricacies of the market with a data-driven approach. Statistical significance achieved through hypothesis testing adds credibility to the insights derived, ensuring that the investors can make informed decisions based on a solid foundation of analysis. From the models, both the R-squared and the adjusted R-squared equals to 1 which proves a perfect regression and both models show a significant linear relationship between the variables and the property prices.

Furthermore, the models facilitate effective communication of complex insights, allowing Mali Safi and Sons to convey the significance of variables and market trends to the investors in a clear and actionable manner. In essence, these analytical tools not only serve as predictive instruments but also as strategic enablers, guiding the Distinguished Group of Parisian Investors towards well-informed and strategic decisions in the realm of real estate.
### Conclusion
Mali Safi and Sons' analytical tools transcend prediction, serving as strategic enablers for the Distinguished Group of Parisian Investors. The models facilitate effective communication of complex insights, allowing for a clear understanding of variables and market trends. In essence, these tools guide investors toward well-informed decisions in the dynamic realm of real estate, ensuring a solid foundation of analysis and strategic navigation through market intricacies.
