This project was a personal challenge to explore further the capabilities of Shiny Dashboards. 

1) The app is quite simple visually, allowing the user to input their own desired parameters to see likelihood of an economic recession in the next two quarters.
2) Initial parameters are taken automatically from indices published by the Federal Reserve's FRED website.
3) If there is missing data in the most recent quarter the program makes a simple extrapolation using ARIMA models to fill in any blanks.
4) The model is designed using a gaussian glm model with the three explanatory variables (Unemployment rate, the lagged yield curve 10year-3year difference, and the OECD's Business Confidence Index.
5) The model is not fine tuned and simply developed to test the ability to create calculated outputs in real time based on interactive inputs.
6) Due to the simplicity of the model note that some years might have negative probabilities.
