<img src="https://github.com/sinyeen/Sinyeen_Portfolio/blob/main/Images/Sinyee's%20Portfolio.gif">

# Hello, folks! <img src="https://github.githubassets.com/images/icons/emoji/unicode/1f467.png?v8" width="30px"> <img src="https://raw.githubusercontent.com/MartinHeinz/MartinHeinz/master/wave.gif" width="30px">
My name is Sin Yee. I am a data science graduate from Monash University who is passionate in big data processing and machine learning. I am excited in the ways data can be used to shape our future. Here are some of the interesting projects I have worked on recently.

<br>

# [Project 1: Award Winning IE Project - Happy Corals](https://github.com/sinyeen/HappyCorals.git) <img src="https://github.githubassets.com/images/icons/emoji/unicode/1f422.png?v8" width="30px"> <img src="https://github.githubassets.com/images/icons/emoji/unicode/1f3d6.png?v8" width="30px">
Our reefs are facing a growing combination of threats such as climate change, water quality, coastal development, and tourism. A majority of Australia's children do not have sufficient information and awareness about the importance of the preservation of coral reefs. It can be a little dry and distant when kids learn about biomes and ecosystems in school. **The main objective of our project is to create a data-driven educational website that is interactive and engaging to help children in Australia learn about coral reefs and things they can do on a daily basis to make a difference for the reefs.**

![](https://github.com/sinyeen/HappyCorals/blob/main/Images/web.PNG)

**Product Link:** [Happy Corals](https://www.happycoral.tk/)

<br>

# [Project 2: Narrative Visualisation Project - Link between Fertility Rate and Income](https://github.com/sinyeen/Fertility_Income_Visualisation.git) <img src="https://github.githubassets.com/images/icons/emoji/unicode/1f476.png?v8" width="30px">
This shiny application is designed to **interactively visualise the relationship between income and fertility** based on the collected data which are wrangled and presented in the `Data Table` Tab. The main question for the visualization project is “Why is fertility rate higher in poor countries?”, and the sub-questions of it are “How education, child mortality rate, and social security system affect the fertility rates?” and “How gross domestic product (GDP) plays a role in the distribution of these three factors?” 

**APP Link:** [Visualisation Dashboard: Link between Fertility Rate and Income](https://sinyee-neo.shinyapps.io/Fertility_Income_Link/)

![](https://github.com/sinyeen/Sinyeen_Portfolio/blob/main/Images/map.JPG)

<br>

# [Project 3: Data Processing for Big Data: Pedestrain Traffic Prediction](https://github.com/sinyeen/Pedestrain_Traffic_Prediction_BigData.git) <img src="https://github.githubassets.com/images/icons/emoji/unicode/1f6a6.png?v8" width="30px">
Develop machine learning models to **predict the pedestrian traffic in the City of Melbourne**. The machine learning models would be further integrated into the streaming platform using `Apache Spark` Streaming to perform prediction. Detailed **feature engineering** is presented in the notebook. The aim of this project is to build models for predicting whether the potential count would go above the threshold of 2000 and also predicting the possible count.

| Use Case | Description | Model |
| --- | ----------- | --- |
| 1 | Predict whether count would go above 2000 for the hours **between 9:00am and midnight** | Binary classification|
| 2 | Predict the possible count for the hours **between 9:00am and midnight** | Regression |

<br>

# [Project 4: EDA & ML: Electric Rotor Temperature Prediction](https://github.com/sinyeen/Electric-Rotor-Temperature-Prediction.git) <img src="https://github.githubassets.com/images/icons/emoji/unicode/1f50c.png?v8" width="30px">
The aim of this project is to make **prediction on rotor temperature (pm)** and find the best model among the other conducted models. A **detailed exploratory data analysis (EDA)** is presented in the first section of the notebook to anaylise and summarise the characteristic of the variables and the relationship between the variables. **Statistical graphics and data visualisation techniques** will be used in the section. The second section of the notebook will be the development of regression model. The process in building the model will be presented in this section in detail. Each model will be compared with explaination and the best one will be selected.

The R-squared value and RMSE of the training and testing set of the models are shown as below:

|Model  |Computation Time|R-square  |RMSE                                                                            |
|-----------|-----------|----------|--------------------------------------------------------------------------------------|
|least square regression (full model)|0.01s|0.462|0.7096|
|least square regression (with interaction terms)|0.01s  |0.678|0.598|
|Ridge regression    |0.7s  |0.393|0.696| 
|Lasso regression        |0.73s  |0.448|0.709     |
|KNN        |2.73s  |0.832|0.716|
|Random forest|274.42  |-0.372|0.827                                    |
