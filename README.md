# Bitumen Density and Viscosity Models

## Introduction

This file shows the details of the models developed for bitumen density and viscosity.
The original data of this research are gathered from 
[Nourozieh et. al. (2015) paper](https://www.onepetro.org/journal-paper/SPE-176026-PA "Density and Viscosity of Athabasca Bitumen Samples at Temperatures Up to 200C and Pressures Up to 10 MPa").

## Models

Five algorithms such as polynomial regression, random forest regressor, adaboost regressor, extra trees regressor and support vector regression are trained to predict density and viscosity. 
Out of all the algorithms, polynomial regression is selected as best performing model for prediction. 
Equations for both density and viscosity are extracted using polynomial regression model in the python codes.

The minimum and maximum values of the temperature and pressures are shown here:

|         | min   | max   |
| ------- |:-----:| -----:|
| T (C)   | 23    | 190   |
| P(MPa)  | 0.91  | 13.88 |
