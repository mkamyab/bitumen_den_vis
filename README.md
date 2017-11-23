# Bitumen Density and Viscosity Models

## Introduction

This file shows the details of the models developed for bitumen density and viscosity.
The original data of this research are gathered from 
[Nourozieh et. al. (2015) paper](https://www.onepetro.org/journal-paper/SPE-176026-PA "Density and Viscosity of Athabasca Bitumen Samples at Temperatures Up to 200C and Pressures Up to 10 MPa").

## Models

Three models has been developed: one for density and two for viscosity.
The steps of created models are presented in this repository. 
The list of saved models that can be used in the applications are listed below:
* _DensityModel.pickle_
* _ViscosityModel_T_and_P_Features.pickle_
* _ViscosityModel_AllFeatures.pickle_

The minimum and maximum values of the temperature and pressures are shown here:

|         | min   | max   |
| ------- |:-----:| -----:|
| T (C)   | 23    | 190   |
| P(MPa)  | 0.92  | 13.88 |

## Using the Models

**UseModels** file shows how to load and use the generated models.
