# Heart-Disease-Prediction

##  Introduction
The Term Heart Disease is often used with interchangeably with the term "cardiovascular disease".
"Cardiovascular Disease" generally refers to condition that involve narrow or blocked blood vessel that can lead to a heart attack,chest pain and stroke.
Heart disease is one of the biggest  cause of morbidity and mortality  among the population of world.
Prediction of the Heart disease is one of the most important subject in the subject of cinical data analysis.
So, our Objective is to build the Machine Learning Model that will predict whether any person is suffering from heart disease or not.

## Machine Learning Formulation

It is very difficult to identify heart disease because of several contibutory risk factors such as  High blood pressure, Diabetes, abnormal pulse rate and many other factors.
Due to such contraints Scientist have turned towards the modern approach  like Machine Leaning to predict the disease.
Machine Learning Proves to be effictve way to making decisions and prediction from the large quantity of data produced y the health care industry.
So, I'll apply Machine Learning approch for classifying whether a person is suffering from heart disease or not.


## Data Set

I've taken data from kaggle (https://www.kaggle.com/ronitf/heart-disease-uci)
In the data set there are 14 columns, which are describe below.

1.) Age: Display the age of the individual.

2.) sex:  Display the gender of the individual in binary format like
          1=male
          0=female
          
3.) chest pain(cp): Display the type of chest pain like
                    0=typical angina
                    1=atypical angina
                    2=non-anginal pain
                    3=asymptotic
                    
4.) trestbps: display the blood pressure reading of the individual in mmHG(Unit).

5.) Cholestrol(chol): display the Cholestrol of individual in mg/dl unit.

6.) Fasting Blood sugar(fbs): compares the fbs value of the individual with 120mg/dl.
                              If fbs> 120 then 19(true)
                              else 0(false).
                             
7.) Resting ECG(restecg): display the resting electrocadiograpgic result.
                          0=normal
                          1=having some abnormality
                          2=left ventricular hyperthrophy
                          
    
8.) thalach(max heart achieved): display the max heart rate achieved by individual.

9.) exang(Exercise induced angina): 1=yes
                                    0=no
                                    
10.) oldpeak: display the values which is integer or float.
              
11.) slope: 1=upsloping
            2=flat
            3=downsloping
            
12.) ca: display the values in integer or float.

13.) Thal: display the thalassemia
           
14.) Target: display whether the person is having heart disease or not.
             0=absent
             1=present
             
             
## Performance Metric
In this we are using the Accuracy as the performance metric.
