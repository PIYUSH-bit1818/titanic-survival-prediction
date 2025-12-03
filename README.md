# Titanic Survival Prediction 🚢

## Objective
Build a machine learning model to predict whether a passenger survived the Titanic disaster.

## Dataset
- Source: Kaggle Titanic – Machine Learning from Disaster
- Train data used for fitting the model
- Test data used for final Kaggle submission

## Approach
1. Loaded and explored the dataset
2. Dropped non-informative features (Name, Ticket, Cabin, PassengerId)
3. Handled missing values:
   - Age, Fare → median imputation
   - Embarked → mode imputation
4. Encoded categorical variables:
   - Sex → binary encoding
   - Embarked → one-hot encoding
5. Used stratified train–validation split
6. Trained a Logistic Regression baseline model
7. Evaluated using accuracy
8. Generated predictions for Kaggle submission

## Model
- Logistic Regression (baseline)
- Stratified validation used to preserve class distribution

## Results
- Validation Accuracy: ~80%
- Kaggle Public Score: 0.77033

## Files
- `titanic_survival.ipynb` → Complete notebook with explanations
- `README.md` → Project overview

## Key Learnings
- End-to-end ML pipeline development
- Importance of stratified splitting
- Handling missing data correctly
- Feature encoding strategies
