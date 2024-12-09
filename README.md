# Here we are developing a chatbot using Natural Language Processing and Logistic Regression.
This bot can easily understand human language and it can able to give instance feedback accordingly.
## Features  
- **Intent Recognition:** Accurately identifies user intent using TF-IDF Vectorizer and Logistic Regression.  
- **Interactive Web Interface:** Provides a seamless user experience via a web application built with Streamlit.  
- **Conversation Logging:** Records user inputs and chatbot responses in a CSV file for analysis and debugging.  
- **Lightweight and Adaptable:** Optimized for environments with limited computational resources.  
## Machine Learning Algorithm Used  
The chatbot uses **Logistic Regression**, a supervised machine learning algorithm, for intent classification.  

### Why Logistic Regression?  
1. **Simplicity:** Easy to implement and interpret, ideal for projects with well-defined intents.  
2. **Efficiency:** Requires less computational power, making it faster to train and deploy.  
3. **Performance:** Works well with structured and labeled datasets.  
4. **Multiclass Support:** Capable of handling multiple intents using the one-vs-rest (OvR) classification strategy.  

### Workflow  
1. **Feature Extraction:** Converts user inputs into numerical representations using **TF-IDF Vectorizer**.  
2. **Model Training:** Trains the Logistic Regression model on labeled intents to map patterns to their respective intents.  
3. **Prediction:** Predicts the intent of new inputs and selects an appropriate response.  
## Technologies Used  

### Programming Languages  
- Python 3.8+  

### Libraries and Frameworks  
- **NLP and Machine Learning:** `nltk`, `sklearn`  
- **Web Interface:** `streamlit`  
- **Data Handling:** `json`, `csv`  
- **Others:** `os`, `datetime`, `random`  

### Dataset  
- A JSON file containing labeled intents and associated patterns, used for training the chatbot to understand user queries. 

## How to run 
-step 1. open terminal.
-step 2. change directory to file location.
-step 3. run the command:
          streamlit run app.py
