# Paris Housing Project Overview

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
  


