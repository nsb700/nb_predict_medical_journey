# NAIVE BAYES PREDICTION OF PATIENT JOURNEY - patient diagnoses, procedures, services and Rx

***

## Description :-

When patients have medical encounters at the doctor's office or hospitals or pharmacies, the major encounters are diagnoses, 
procedures, services and Rx. These encounters lie over the entire gamut of cost - from cheap to expensive. So, it is beneficial
to get a sense of what encounters a patient may likely experience in future - so that it can possibly be dealt with in advance - 
either by accounting in the budget or by member-intervention or accounting for the risk. Knowing versus not knowing can be a 
huge difference in ROI. 

The solution presented here, shows how a new encounter of BETA BLOCKER use by a patient can be predicted - Although the solution 
can be used to predict any one of 160 different encounters including diagnoses, procedures, service and Rx.

As you will see, this tool benefits the following entities : -

(1) Provider-end (hospitals, doctors, physicians, nurses, clinicians),

(2) Payer-end (risk managers, clinical managers, actuary, medical economics, finance). 

The prediction gives a quick sense of severity of a patient (member). This is valuable in following scenarios :-

(1) Effective and Efficient Member Intervention,

(2) Budgeting,

(3) Accurate Risk Assessment

(4) Reduce Costs - Efficient and targeted member intervention reduces costs,

(5) Reduce financial burden of most expensive procedures,

(6) Substantially grow ROI.

In real world, this would not be the only tool at disposal. A well-informed decision would have to made by weighing predictions 
of this model with other tools at disposal. For ex: Let's say a clinical team at the payer-end already has been using medical charts
for selecting patients to contact for member intervention.
After analyzing medical charts (also see https://github.com/nsb700/statistical-indexer-medical-charts), if the clinical team is able to find say 
100 members, this tool can further help to focus on members of interest based on high cost items. It can reduce the member set from 100
to way fewer members resulting in more ROI.

Coding is done using Python. Intermediate outputs are printed in the notebook for clarity.

Files are arranged as below - 

(1) Data preparation - Step_01_Data_Preparation_(for_Prediction_of_Patient_New_Beta_Blocker_Use).ipynb
    
    Output of Data Preparation - step_01_output.zip
    
(2) Prediction with Naive Bayes - Step_02_NaiveBayesClassifier_(for_Prediction_of_Patient_New_Beta_Blocker_Use).ipynb

***

