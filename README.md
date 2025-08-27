# Deep Learning Project using ANN :-

## In these project we predict bank customer churn or not.

## Below Steps for Create this Project:-

## Data Pre-Processing :-
- Take a Bank Data in CSV Formate and convert into Dataframe using pandas.
- Remove unnecessory Data and Data cleaning.
- Convert Textual Data into Numerical with LabelEncoding and OneHotEncoding.
- after that devide data into depent and indepent features(Input-Output)
- Apply Train_Test_Split on Data.(80%Train, 20%Test)
- Perform Scalling by using StandardScaler.

## Build Model :-
- Using Sequential and Dense from Keras for Build Model.
- and Using relu and sigmoid for activation in Hidden Layer.
- Apply Optimizer for Compile Model.
- Train Model Using Train_Test Data.
- Model Save by using h5 File

## Prediction :-
- Here we are using Streamlit for Taking Input data for Prediction.
- Apply Pre-Processing on Prediction Data.
- Load Model file and Perform Prediction.
- Here we Predict, If Prediction Prob above 0.5 then Customer like to Churn and Below 0.5 then Not Churn....
