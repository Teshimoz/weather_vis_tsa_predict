# Weather Data Visualizations, TSA, Prediction
*All the data collected with scripts from another repository ([weather](https://github.com/Teshimoz/weather), link to my fork for two sensors)*

<b>Rendered notebook:</b><br>
https://nbviewer.org/github/Teshimoz/weather_vis_tsa_predict/blob/1dd869033fc6bc2e1ae1ed716c5a9aa7de89131d/weather_vis_tsa_predict.ipynb

<b>Project description:</b><br>
Visualizations of local weather data like temperature, humidity, pressure. Time Series Analysis, Prediction of temperature using Prophet tool.<br>
The purpose was to get better understanding of local climate and microclimate.<br><br>
Used plotly and matplotlib+seaborn for visualisations, pandas to work with dataframes, imported from SQL db. Used statsmodels.tsa.seasonal to exctract trend and season components from the data, applied Prophet tool for predictions, improved by hyperparameter tuning.<br>
<br>This project contain following main parts:
* Data preprocessing
* Visualizations of data in different perspectives to explore it better and discover some patterns
* Time Series Analysis to understand trends and seasons
* Prediction of temperature by Prophet tool
