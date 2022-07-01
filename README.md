# Heart_Disease_Classification

This mini project is an attempt to build a machine learning model that can predict whether a patient has any heart disease or not, based on various medical attributes. 

The main steps involved in the making of the project are:
### 1.Problem Definition
This is a binary classification problem where we predict a patient has heart disease or not (1=heart disease, 0=no heart disease) based on various parameters such as age, sex, chest pain type, cholesterol, maximum heart rate, etc.

### 2.Data
The data used in this project has been collected from the UCI Machine Learning repository. Link:  https://archive.ics.uci.edu/ml/datasets/Heart+Disease
It is also available on Kaggle. Link: https://www.kaggle.com/datasets/ketangangal/heart-disease-dataset-uci

### 3.Evaluation
The project would be fruitful if we can attain 90-95% accuracy in predicting whether a patient truly has any heart disease or not.

### 4. Features
A total of 14 attributes are used in this project. They are described one by one as follows:
i. age - age in years
ii. sex - (1 = male; 0 = female)
iii. cp - chest pain type
* 0: Typical angina: chest pain related decrease blood supply to the heart
* 1: Atypical angina: chest pain not related to heart
* 2: Non-anginal pain: typically esophageal spasms (non heart related)
* 3: Asymptomatic: chest pain not showing signs of disease trestbps - resting blood pressure (in mm Hg on admission to the hospital) anything above 130-140 is typically cause for concern
iv. chol - serum cholestoral in mg/dl
v. serum = LDL + HDL + .2 * triglycerides above 200 is cause for concern
vi. fbs - (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false) '>126' mg/dL signals diabetes
vii. restecg - resting electrocardiographic results
* 0: Nothing to note
* 1: ST-T Wave abnormality can range from mild symptoms to severe problems, signals non-normal heart beat
* 2: Possible or definite left ventricular hypertrophy, Enlarged heart's main pumping chamber
viii. thalach - maximum heart rate achieved
ix. exang - exercise induced angina (1 = yes; 0 = no)
x. oldpeak - ST depression induced by exercise relative to rest looks at stress of heart during excercise unhealthy heart will stress more
xi. slope - the slope of the peak exercise ST segment
* 0: Upsloping: better heart rate with excercise (uncommon)
* 1: Flatsloping: minimal change (typical healthy heart)
* 2: Downslopins: signs of unhealthy heart
xii. ca - number of major vessels (0-3) colored by flourosopy
* colored vessel means the doctor can see the blood passing through
* the more blood movement the better (no clots)
xiii. thal - thalium stress result
* 1,3: normal
* 6: fixed defect: used to be defect but ok now
* 7: reversable defect: no proper blood movement when excercising
xiv. target - have disease or not (1=yes, 0=no) (= the predicted attribute)

### 5. Modelling
For this project in particular, we have used three different classification models :
* 1. LogisticRegression
* 2. KNearestNeighbors
* 3. RandomForestClassifier

### 6. Experimentation
We have evaluated our models thoroughly and tried to tune the various hyperparameters of the models used, to check if there can be any improvement in the accuracy of the model

### Necessary Packages
* 1. Pandas
* 2. NumPy
* 3. Matplotlib
* 4. Seaborn
* 5. Scikit-learn
