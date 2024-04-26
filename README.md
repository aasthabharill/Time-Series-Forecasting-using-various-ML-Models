# Time-Series-Forecasting-using-various-ML-Models
This is a brief research review on the performance of different Machine Learning Models for the problem of time series forecasting by framing it as a supervised regression. Please find the report uploaded under the name "Time Series Analysis - ML Proejct Report"

## Project Statement
This was done as a project for the course BITS F464 Machine Learning which described the project statement as follows:
Which hypothesis classes are better tuned for time series prediction? 
A time series dataset is nothing but a data in the form x1, x2, · · · xT , where each of the xi ∈ Rd. This can be converted to a supervised regression problem by asking - Can you predict the value next time given the previous k values? So, the aim is to identify the right hypothesis class to do this problem.
1. First, setup the ML problem correctly - (i) What is the right metric to evaluate the model? (ii) How should you do the train/valid/test splits? etc.
2. For each model of hypothesis class, do a hyper-parameter optimization and accordingly select the best model.
3. Comment on the performance of linear models, decision trees and neural networks for time series. Can you identify where the errors in these models are coming from? and propose a solution?

Submit a report (not exceeding 5 pages) with the following sections:
1. Problem Statement
2. Methodology
3. Experimental Results and Validation
4. Conclusion and Future Work

## Overview of uploaded files
Please refer to the final report that outlines the results and follows the format as stated above. I used 2 different datasets, and so there are separate code files for each wherein the results and plots can be clearly seen for better understanding. The project statement asks for very specific things, because of which I did not pre-process the data as per how a state-of-the-art time series forecasting model should and stuck to what was asked - but the ideal way of going about such a problem has been stated in the last section of the report in "Future Work". I have also added an 'Appendix Section' to the report that contains the plots generated during pre-processing and a guiding table that outlines the factors to be considered while performing forecasting. 
