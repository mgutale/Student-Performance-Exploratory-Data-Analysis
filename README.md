# Student-Performance-Exploratory-Data-Analysis

## Introduction

The purpose of undertaking this task is to understand and explore the student performance data and to select features that are fit to perform machine learning tasks. I will be performing data processing and cleaning techniques if necessary to resolve potential bottlenecks and limitations of the raw data before performing data visualisations to presenting a narrative of the data. I may have to potentially feature engineer if I deemed fit.

Dataset

The data is downloaded from UCI’s machine learning repository. It’s a multivariate dataset consisting of 649 instances and 33 attributes. The raw data is based on student achievement in secondary school education of two Portuguese schools. The data attributes include student grades, demographic, social and school related features) and it was collected by using school reports and questionnaires. Two datasets are provided regarding the performance in two distinct subjects: Mathematics (mat) and Portuguese language (por). The datasets were used to model binary / five level classification and regression tasks. The target attributed is G3 which is the final grade.

## Method

In this notebook, I will be performing the EDA by following this approach:

Understanding the problem: Look at each variable and importance to the problem
Univariate analysis: Focus on dependant variable (G3 – Final grade) and learn more about it
Multi-variate analysis: try to understand how to dependant and independent variables relate to each other.
Data Cleaning: clean and handle any missing values and duplicates
Test assumptions: test to check if our data conforms to assumptions by multivariate techniques.
Outline of the EDA

The code in this report will perform the following:

Retrieve the data
Preview the data
Clean and process
univariate analysis
multi-variate analysis
Plot numerical distribution and categorical data
Conclusions