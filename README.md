# Starbucks Recommendation

## Summary

Using three datasets provided by Starbucks, 
this work aims to get the data, clean it, explore, visualize and understand, 
and, finally, model a predictor to check if a customer would take or not an offer. 
Further, a blog post is available at: ,describing all the steps and conclusions made.

## Folder organization

The project is organized as follows:
 
- data 
|- portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.) 
|- profile.json - demographic data for each customer 
|- transcript.json - records for transactions, offers received, offers viewed, and offers completed  
- Starbucks_Capstone_notebook.ipynb - notebook with the clean, explore, vizualize and model 
- README.md 
- docs - images from the analysis 
- processed_data 
|- offers_transcript.csv - transactions during the offers period 
|- processed_offers.csv - dataset of offers used to analyze and train the model 
- models 
|- final-best-catboost.pkl - the trained classifier to recomend to send a offer or not


## Instalation

The code runs in Python 3.8.2 and requires the following libraries:
- Numpy (1.16.2)
- Pandas (0.24.2)
- Plotly (4.14.3)
- Tqdm (4.31.1)
- PyCaret (2.3.1)

### Instructions:
Run the Python Notebook with the data provided to import the data, explore the data, vizualize the data 
and create an Auto-ML model that predicts if the user will take the offer or not

## Acknowledgements & Licensing

The code provided here is free to use and it is under MIT Licensing.