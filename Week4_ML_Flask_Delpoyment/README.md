## Model deployment using Flask ##
"""
This provide a simple procedure on model deployment using flask


Prerequisites
Install  pandas, Pandas,Scikit Learn, and Flask for API.

1. Create a virtual environment
pip install virtualenv
virtual enviroment nevn

Windows: mypthon\Scripts\activate

The project parts:

1. model.py: contains the model codes.
2. app.py: contain Flask API codes.
3. templates: contain html template (index.html)
4. static: contains the css folder for style.css


Running the project:

1. In project home page, create a machine learning model from command prompt run python model.py
 Serialized version of the model is created into a new file model.pkl
 
 
2.To start flask ApI, run python app.py
Flask will run on port 5000.

3. Navigate to url http://127.0.0.1:5000/ or http://localhost:5000/ 

4. Enter valid values into 3 boxes and click predict.

5. The result should be displayed on html page.








Flask version: 1.1.2 conda install flask (or) pip install Flask


Created on Mon Jul  5 18:56:26 2021

@author: william
"""

