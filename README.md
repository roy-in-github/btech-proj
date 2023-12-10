# Stock-Market-Predictor
## LSTM Price Prediction using Streamlit and FastAPI
This project is an implementation of a machine learning model using LSTM to predict stock prices. The front-end of the application is built using Streamlit, and the back-end is built using FastAPI. The model is trained using historical stock data, and the predicted prices are displayed on a graphical user interface.

## Usage

To run the application, first start the FastAPI server:

`uvicorn foldername.main:app --reload`
> this foldername is the folder in which main.py is present

Then, in a separate terminal, start the Streamlit app:

`streamlit run app.py`
> In order to use streamlit framework you should create a different environment in anaconda

You should now be able to access the application in your web browser at http://localhost:8501.
