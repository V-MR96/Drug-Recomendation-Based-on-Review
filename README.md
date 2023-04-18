# Drug-Recomendation-review
Based on the reviews given by user our app trys to predicts underling disease and suggest few drugs 💊 corresponding to the predicted disease. 

- The file final.pdf will be helpful in understanding what we are trying to achive 
- 1. Poject-Drug-EDA.ipynb : File has a EDA(Exploratory Data Analysis) on the data. 
- 1.1 webapp2.py : Its is a streamlit based app which suggest drugs for 3 conditions (1. Depression; 2.High Blood Pressure; 3. Diabetis)
- 2. Review-app.ipynb : Here few models are trained with reviews in our data so that it trys to match with a condition when our user provides with a review.
- 2.1 Review-app.py : Its is a streamlit based app which suggest drugs for three conditions (1. Depression; 2.High Blood Pressure; 3. Diabetis) by taking a review from the user. 


Data-set 📚 for our model is taken from [UCI Machine Learning Repositories](https://archive.ics.uci.edu/ml/datasets/Drug+Review+Dataset+%28Drugs.com%29) which has a lot of conditions but the models are trained only 3 condition (1. Depression; 2. High Blood Pressure; 3. Diabetis)  by tweaking the code a little you can change it a
