# Prediction of density and viscosity of Athabasca bitumen

## Introduction

This file includes the details of the machine learning models developed for prediction of density and viscosity of Athabasca bitumen. The original data used for this research study is collected from [Nourozieh et al. (2015) article](https://www.onepetro.org/journal-paper/SPE-176026-PA "Density and Viscosity of Athabasca Bitumen Samples at Temperatures Up to 200C and Pressures Up to 10 MPa").

## Machine Learning Algorithms

Five machine learning algorithms, including second-order polynomial regression, random forest, adaboost, extra trees, and support vector regression are trained to predict density and viscosity of Athabasca bitumen. Out of all the examined algorithms, polynomial regression is selected as the best performing model for predictions. Expressions for both density and viscosity are extracted using polynomial regression model in the python codes.

The minimum and maximum values of the temperature and pressure are as follows:

|        | Minimum | Maximum |
|--------|---------|---------|
| T (°C) | 23      | 190     |
| P (MPa)| 0.91    | 13.88   |
