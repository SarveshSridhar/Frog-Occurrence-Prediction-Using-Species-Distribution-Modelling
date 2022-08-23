# Frog Occurrence Prediction Using Species Distribution Modelling

Prediction of Occurrence of Frog in a region of Australia. A Species Destribution Model is built only using the geographical features like minimum temperature, maximum temperature, soil density, precipitation volume.



## Problem Statement

Frogs are an indicator species. This means they are a go-to for scientists wanting
to find out more about the environmental health of a particular ecosystem.
Because they have permeable skin, frogs are very sensitive to pollutants, and
because they can live on both land and in the water, they are a good indicator of
the health of these two different environments. As indicators of ecological health
and proxies for biological diversity, the disappearance of frogs is of great
concern. Where frogs occur, we see healthy, thriving, resilient ecosystems.
Where the frogs have disappeared, we see ecosystems in poor health.
The objective here is to build a Species Distribution Model (SDM) which predicts
the occurrence of a single species of frog for a single location using a single data
source at a coarse spatial resolution. Species distribution models are one of the
most widely used ecological tools, a cornerstone in many countries worldwide of
environmental regulation and conservation.
## Motivation

All the 2030 Sustainable Development Goals (SDGs) are underpinned by healthy
ecosystems. This means we won’t reach our goals if we don’t prevent and
reverse the loss of healthy ecosystems. Hence to take care of the ecosystem we
have designed a model to predict the frog occurrences in a certain region.
## Methodology

In the Species Distribution Modelling, we cannot use spatial and time features to predict. Only geographical features of the spatial and time coordinates can be used.

So we get the geographical features of particular region and time from **"TerraClimate"** dataset from Microsoft Planetary database.

Prilimnary features extracted are:

    1. Soil Density
    2. Precipitation
    3. Min Temperature
    4. Max Temperature

We use these four features to predict the occurrence of the frogs in a region.
More features can be extracted like elevation height, average wind speed, slope, orientation, rock exposure, soil type, etc.

## Output

### Frog Occurrences in New Sydney

![App Screenshot](https://github.com/SarveshSridhar/Utility-Rasa-ChatBot/blob/master/occurrences.PNG)

### Prediction of Litoria Fallax (Frog Species) with different geographical conditions

![App Screenshot](https://github.com/SarveshSridhar/Utility-Rasa-ChatBot/blob/master/geographical.PNG)

## Logistic Regression

![App Screenshot](https://github.com/SarveshSridhar/Utility-Rasa-ChatBot/blob/master/logistic.PNG)

## Gaussian Naive Bayes

![App Screenshot](https://github.com/SarveshSridhar/Utility-Rasa-ChatBot/blob/master/logistic.PNG)

## Support Vector Machine

![App Screenshot](https://github.com/SarveshSridhar/Utility-Rasa-ChatBot/blob/master/logistic.PNG)



