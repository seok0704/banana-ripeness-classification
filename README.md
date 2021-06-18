# Classification of Banana Ripeness 
The purpose of this project is to provide a cost effective solutions to consumers for detection of banana ripeness level. The banana is specifically chosen for their relatively large changes in emission of ethylene during ripening, fast ripening time, availability and colour change. 

The implementation of the solution is a device that will classify the ripeness of fruit when placed inside.  An Arduino Nano microcontroller will be used to gather data from sensors, apply the classification model, and display the ripeness classification on an OLED display. The work includes data collection, creating classification model, programming the Arduino and its logic, and a enclosure for validation.

The variables that were measured are the gas levels from MQ2, MQ3 and MQ9 which are temperature and the humidity. The experiment was conducted at the same time every day for 13 days using 7 samples of banana. This experimental design allows for low cost and time while offering enough data for the classification model.  Additionally, the pictures of the bananas were taken prior to the data collection to analyze and compare the gas level with the skin color of the banana. 

Since there are no specific classes or levels of ripeness, KMeans is implemented to identify the ideal classes and segregate the samples to different levels of ripeness. 

For additional study, the classification of ripeness level through image recognition is developed and deployed on web application using Flask Framework. 
