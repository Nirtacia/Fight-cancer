# Identifying serious medical conditions at an early stage

Final project for the Building AI course

## Summary

Create systems and devices for analyzing exhaled breath and thereby detecting medical conditions at an early stage. The devices are to be installed at workplaces, schools, stores etc. 

## Background

If you feel really ill and need help, you naturally seek medical attention. However: people suffering from a number of serious medical conditions, e.g. certain forms of cancer, don't necessarily feel ill or understand that they are sick until it is already to late for them to get successful treatment. What if there was a way of predicting serious diseases long before you even suspect you have them?

## How is it used?

Measuring the composition of exhaled breath gives us a clue of the condition of our lungs, but can also be used to predict other serious diseases, even before we experience any symptoms. Therefore, devices that collect samples of exhaled breath would be installed in smartphones, headsets, smartwatches etc., but also at public locations such as schools, workplaces, stores, hospitals, trains and buses. When a person uses his or her smartphone, or passes by one of the public devices, an exhaled breath sample is taken. If the analysis of the sample indicates anything alarming, the individual in question is contacted and encouraged to seek medical attention as soon as possible.

When using a smartphone or some other private appliance, the identification part is not a problem. Your breath can easily be analyzed and the result be presented in an app or in a text message. When using public devices however, we will also have to solve the problem of identifying people. If the individual uses a credit card or presents an ID card in connection with the sample beeing taken, the problem is solved. However, in public areas where people don't identify themselves, there will be a need of more advanced techniques, e.g. facial recognition. 

## Data sources and AI methods

The system requires data collected from several systems:

| Source of data              | Description |
| ------------------- | ----------- |
| Healtcare systems    | Breath samples from people diagnosed with serious medical conditions need to be collected and used as training data when teaching the AI model.|
| Facial recognition   | Facial recognition systems can be used to identify people in public areas. Needs to be connected to the population register. ||
| Population register   | To be able to send a notice when people are identified via public devices.        |

## Challenges

What does your project _not_ solve? Which limitations and ethical considerations should be taken into account when deploying a solution like this?

## What next?

How could your project grow and become something even more? What kind of skills, what kind of assistance would you  need to move on? 


## Acknowledgments

Analysis of Exhaled Breath for Disease Detection, https://doi.org/10.1146/annurev-anchem-071213-020043
Dogs Are Teaching Machines to Sniff Out Cancer, https://www.the-scientist.com/news-opinion/dogs-are-teaching-machines-to-sniff-out-cancer-68469

* list here the sources of inspiration 
* do not use code, images, data etc. from others without permission
* when you have permission to use other people's materials, always mention the original creator and the open source / Creative Commons licence they've used
  <br>For example: [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
* etc
