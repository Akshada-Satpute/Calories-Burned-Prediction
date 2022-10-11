
# Calories-Burned-Prediction

Using this [application](https://caloriespredictor.herokuapp.com/) you will be able to check how many calories you would burn during a specific duration. This app takes some information about you such as your age , gender , exercise duration etc. and then this app evaluates the amount of calories you would burn.  

## Project Description

- This project implemented various concepts such as EDA, Correlation, Multicollinearity, etc.
- This application is made up of a simple machine learning algorithm(`Linear Regression`) from the sklearn library. 
- Further, a front end is created using Streamlit and deployed in Heroku.

## Dataset Description

- Dataset link: (https://www.kaggle.com/datasets/fmendes/fmendesdat263xdemos)
- Observations: 15000 
- Features: 8

### Data Dictionary
						
- User_ID: The ID of the person which is unique
- Gender: Gender of the person
- Age: Age of the person
- Height: Height of the person in cm
- Weight; Weight of the person in kg
- Duration: Duration of the person's exercise/activity
- Heart_Rate: Heart rate per min of the person
- Body_Temp: A body temperature of the person in Celcius
- Calories: Calories burned in kilo calories


## Running Streamlit File

After downloading and saving the streamlit file (`app.py`) into a certain directory, you have to open `Command Prompt`.In your command prompt change the directory to the directory where the streamlit file is saved and then type:

```
streamlit run app.py
```

After couple of seconds the WebApp pops up in your browser and then you can modify it with your prefered Interpreter.For saving changes on the WebApp and streamlit file you have to press `Ctrl + S` while you are into your interpreter.


