# Valeo-defect-prediction

Valeo created a challenge to detect defects on a production line.

In this repo, you can find:
- predict_defect.ipynb: A notebook where I tested several models. The best model is a XGBClassifier,
- best_model.ipynb: A notebook with all the parameters I chose,
- app_predict_defect.py: A web application using Streamlit,
- model.pkl: My model saved as pickle file,
- data file: You can find data and a prediction I submitted for the challenge, and an example to submit to the application.

You can run the Streamlit Application with the command `streamlit run app_predict_defect.py`.
This application is alose deployed with Heroku : https://predict-defect-valeo-challenge.herokuapp.com/
