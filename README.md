The global average temperature has risen by approximately 0.85°C in the past 
century due to climate change and is projected to increase by up to 5.5°C by the 
end of the 21st century (IPCC 2013; Mazdiyasni et al. 2017; Rohini et al. 2016). 
In India, the mean annual temperature increased by about 0.51°C from 1961 to 
2007, with more frequent warm days (Kothawale et al. 2010). This rise in 
maximum temperature can lead to extreme heatwaves, impacting ecosystems, 
hydrological systems, and social welfare, necessitating improved daily 
maximum temperature predictions (Mazdiyasni et al. 2017; Murari et al. 2015). 
Temperature variations are influenced by factors like altitude, latitude, land use, 
wind patterns, ocean currents, and proximity to the sea. Traditional methods for 
forecasting temperatures often require complex physical simulations, while 
data-driven approaches (DDAs), especially those using artificial intelligence 
(AI) and machine learning (ML), offer new potential (Cifuentes et al. 2020; 
Scher 2018; Tran et al. 2021).
Deep learning (DL), a subset of ML, has shown high efficiency in capturing 
complex data relationships without explicit physical process modeling, making 
it suitable for hydroclimatic analysis and modeling (Khan and Maity 2020; 
Kratzert et al. 2019b; LeCun et al. 2015). Recent studies have demonstrated the 
effectiveness of DL in forecasting hydroclimatic variables like temperature, 
streamflow, and rainfall across different scales. Examples include using twodimensional convolutional neural networks (CNNs) for weather information 
extraction (Liu et al. 2016), long short-term memory (LSTM) networks for 
rainfall-runoff processes (Hu et al. 2018), and hybrid models like Conv1D and 
multi-layer perceptron (MLP) for rainfall forecasting (Khan and Maity 2020). 
These studies highlight the superior performance of DL models compared to 
traditional methods.
Specifically, studies on temperature forecasting using AI-based ML/DL 
approaches have shown promising results. For instance, Kisi and Shiri (2014) 
used adaptive neuro-fuzzy inference systems (ANFIS) and artificial neural 
8
networks (ANN) to predict monthly air temperature in Iran. Kisi and Sanikhani 
(2015) evaluated five different DDAs, finding support vector regression (SVR) 
most effective. Other studies have compared models like SVR, MLP, and 
LSTM for temperature predictions in various regions, demonstrating the 
advantages of DL approaches (Salcedo-Sanz et al. 2016; Papacharalampous et 
al. 2018; Zhang et al. 2020; Tran et al. 2020; Kreuzer et al. 2020).
Summarizing these studies, DL models generally outperform other approaches 
but often use limited input variables and still show significant root mean square 
error (RMSE) values, indicating room for improvement. This study aims to 
develop a hybrid DL model combining the best-performing DL models to 
predict daily maximum temperature in major Indian cities and foresee heatwave 
events. The hybrid model's performance is compared with individual DL 
models, ML models, and popular weather apps like AccuWeather, real-time 
weather system, and Weather Underground to demonstrate its benefits.
