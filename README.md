# Heart Attack Prediction with classification
## Features explained
* Age
* Sex
* exng - exercise induced angina (1 = yes; 0 = no)
* ca - number of major vessels (0-3)
* cp - Chest Pain type chest pain type
    * Value 1: typical angina
    * Value 2: atypical angina
    * Value 3: non-anginal pain
    * Value 4: asymptomatic
* trtbps - resting blood pressure (in mm Hg)
* chol - cholestoral in mg/dl fetched via BMI sensor
* fbs - (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
* rest_ecg - resting electrocardiographic results
    * Value 0: normal
    * Value 1: having ST-T wave abnormality (T wave inversions
    and/or ST elevation or depression of > 0.05 mV)
    * Value 2: showing probable or definite left ventricular
    hypertrophy by Estes' criteria
* thalach - maximum heart rate achieved
* oldpeak - Previous peak
* slp - slope the slope of the peak exercise ST segment
    * Value 0: upsloping
    * Value 1: flat
    * Value 2: downsloping
* caa - Number of major vessels
* thall - Thalium stress result ~(0,3)
* target - 0= less chance of heart attack 1= more chance of heart attack

## Dataset analysis results

### Correlations
**Positiv correlations**
* thalachh - output = 0.4
* thalachh - slp = 0.4
* cp - output = 0.4

**negativ correlations**
* oldpeak - slp = -0.6
* thalachh - age = -0.4
* cp - exng = -0.4
* exng - thalachh = -0.4