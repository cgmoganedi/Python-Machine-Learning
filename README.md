# Python-Machine-Learning

## Predicting Diabetes

There are 768 rows of csv entries with data about each patient,
10 colums corresponding to the following 0 - 8 attriblues (data
about the patient) with the 9th being the target of classification,
this class is binary in our case (diabetic or not).

0 => Number of pregnancies => num_preg
1 => Plasma glucose conentration => glucose_conc (mass/vol)
2 => Diastolic blood pressure => disatolic_bp (mm Hg)
3 => Triceps skin fold thinkness => thickness (mm)
4 => 2-hour serum insulin => insulid (mu U/ml)
5 => Body Mass Index (weight in kg/(height in m)^2) = bmi
6 => Diabetes pedigree function => diab-ped
7 => Age => age (years)
8 => skin what the hel (thickness too)
9 => Diabetic (class variable (T/F)) => diabetes

Sample:
    6, 148, 72, 35, 0, 33.6, 0.627, 50, 1.379, TRUE
    which means:
    The patient has had 6 pregnancies ...

    and is diabetic

    1, 85, 66, 29, 0, 26.6, 0.351, 31, 1.1426, FALSE
    which means:
    The patient has had 1 pregnancy ...
    
    and is not diabetic 