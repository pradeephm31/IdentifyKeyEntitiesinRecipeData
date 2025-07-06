# IdentifyKeyEntitiesinRecipeData
> The goal of this assignment is to train a Named Entity Recognition (NER) model using Conditional Random Fields (CRF) to extract key entities from recipe data. The model will classify words into predefined categories such as ingredients, quantities and units, enabling the creation of a structured database of recipes and ingredients that can be used to power advanced features in recipe management systems, dietary tracking apps, or e-commerce platforms.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)

## General Information
1. Data Preparation end EDA	
	- This step involves generation token, categorize tokens to labels(unit, ingredient, quantity) and perform analayis  

2. Feature Extraction for CRF and Training
	- Creation of feature dictionary , weight dict , extarction of features with class weights and CRF Model Train

3. Prediction nad Model Evaluation
	- Evaluate the Model both and train and validation data
   
4. Error Analysis on Validation Data 
	- Perform Errpr Analysis of the Validation Data



## Technologies Used
- numpy version
- pandas version
- seaborn version
- matplotlib version
- sklearn_crfsuite
- spacy
- sklearn version



## Acknowledgements
Give credit here.
- This project was inspired by NLP and Lecture Notes as part of IIIT-B PG Program in a ML and AI


## Contact
Created by [@pradeephm31] - feel free to contact me!
