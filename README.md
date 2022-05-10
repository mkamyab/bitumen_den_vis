{\rtf1\ansi\ansicpg1252\cocoartf2580
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\froman\fcharset0 Times-Roman;\f1\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\margl1440\margr1440\vieww28600\viewh15380\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs36 \cf0 Bitumen Density and Viscosity Models
\fs24 \
\

\fs28 Introduction
\fs24 \
\
This file shows the details of the models developed for bitumen density and viscosity.\
The original data of this research are gathered from \
[Nourozieh et. al. (2015) paper](https://www.onepetro.org/journal-paper/SPE-176026-PA "Density and Viscosity of Athabasca Bitumen Samples at Temperatures Up to 200C and Pressures Up to 10 MPa").\
\

\fs28 Models\

\fs24 \
Five algorithms such as polynomial regression, random forest regressor, adaboost regressor, extra trees regressor and support vector regression are trained to predict density and viscosity. \
Out of all the algorithms, polynomial regression is selected as best performing model for prediction. \
Equations for both density and viscosity are extracted using polynomial regression model in the python codes.\
\
The minimum and maximum values of the temperature and pressures are shown here:\
\
|         | min   | max   |\
| ------- |:-----:| -----:|\
| T (C)   | 23    | 190.4  |\
| P(MPa)  | 0.91 | 13.88 |\

\f1 \
}