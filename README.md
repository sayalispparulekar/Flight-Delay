# Flight-Delay
Predicting Flight Delays using Machine Learning Models

In this repository , I develop a model aimed at predicting flight delays at take-off. 

From a technical point of view, the main aspects of python covered throughout the notebook are:

    visualization: matplolib, seaborn, basemap
    data manipulation: pandas, numpy
    modeling: sklearn, scipy
    class definition: regression, figures

1. Cleaning

    1.1 Dates and times
    
    1.2 Filling factor

2. Comparing airlines

    2.1 Basic statistical description of airlines
    
    2.2 Delays distribution: establishing the ranking of airlines

3. Delays: take-off or landing 

4. Relation between the origin airport and delays

    4.1 Geographical area covered by airlines
    
    4.2 How the origin airport impact delays
    
    4.3 Flights with usual delays 

5. Temporal variability of delays

6. Predicting flight delays

    6.1 Model no.1: one airline, one airport
    
        6.1.1 Pitfalls
        
        6.1.2 Polynomial degree: splitting the dataset
        
        6.1.3 Model test: prediction of end-January delays
        
    6.2 Model no.2: one airline, all airports
    
        6.2.1 Linear regression
        
        6.2.2 Polynomial regression
        
        6.2.3 Setting the free parameters
        
        6.2.4 Model test: prediction of end-January delays
        
    6.3 Model no.3: Accounting for destinations
    
        6.3.1 Choice of the free parameters
        
        6.3.2 Model test: prediction of end-January delays


