# Identifying serious medical conditions at an early stage

Final project for the Building AI course

## Summary

Create systems and devices for analyzing exhaled breath and thereby detecting medical conditions at an early stage. The devices are to be installed at workplaces, schools, stores etc.

## Background

When feeling really unwell, you naturally seek medical attention. However: people suffering from some serious medical conditions, e.g. certain forms of cancer, don't necessarily feel ill or understand that they are going to fall ill, until it is already to late for them to be treated successfully. What if there was a way of predicting serious diseases months, or perhaps even years, before you even suspect you're developing such a disease?

## How is it used?

We already know that measuring and analyzing the composition of exhaled breath can give us information of the condition of our lungs (asthma etc.). But it can also be used to predict other serious diseases, even before any symptoms are experienced. Therefore, devices that collect samples of exhaled breath would be installed in smartphones, headsets, smartwatches etc., but also in public areas such as schools, workplaces, stores, hospitals, trains, buses etc. When a person uses his or her smartphone, or passes by one of the public devices, an exhaled breath sample is taken. AI analyzes the sample and if the analysis indicates anything alarming, the individual is contacted and encouraged to seek medical attention as soon as possible.

When using a smartphone or some other private appliance, the identification part is not a problem. Your breath can easily be analyzed while you're using your phone and the result can be presented in an app. With the use of public devices however, there is also the issue of identifying people. If the individual uses a credit card or presents an ID card in connection with the sample beeing taken, the problem is solved. In public areas where people don't have to identify themselves, identification has do be done using more advanced techniques, e.g. facial recognition. 

## Data sources and AI methods

A full-scale system would require data collected from several systems and databases, for example:

| Source of data              | Description |
| ------------------------------ | ----------- |
| Healtcare systems         | Breath samples from people diagnosed with serious medical conditions need to be collected and used as training data when teaching the AI model which indicators to react to.|
| Facial recognition   | Facial recognition systems can be used to identify people in public areas. This requires that images of the population is collected and stored.  ||
| Population register   | When a person is identified e.g. via facial recognition systems, the population register can be used to find that persons address and send a message by mail or e-mail.       |

## Challenges

First and foremost, a solution like this certainly raises ethical questions. Monitoring people is, as we all know, not an uncontroversial issue. At what point do the benefits outweigh the threat to privacy?

Secondly: even if the presented solution successfully detects diseases at an early stage, it is still relying on people taking action based on the outcome of the result of the screening. If notifications are ignored, people still will go untreated. Moreover, it's likely to expect that the model fails to deliever results with one hundred percent certainty, which would mean that individuals at risk of developing a serious disease still won't be alerted in time. 

## What next?

A first step would be to conduct a feasibility study:
* Which diseases are generally detected too late? Would it be possible to detect some of them earlier by using exhaled breath samples?
* How many people are affected?
* What ages are affected? Children? Elderly people?
* How much does the palliative care cost? What is the socio-economic impact of (young?) people dying prematurely?

The feasability study will hopefully pinpoint what specific diseases we can conquer using this technique, what age groups that are most affected and so on. The results of the feasibility study will hence point out the direction for the next step. If the study shows that the effort should be made among young people, it might be sufficient to implement the technique in smartphones and other devices used by youngsters. If, instead, more is to be gained by screening elderly people, maybe a smartphone device isn't the best way. 

## Acknowledgments

* Analysis of Exhaled Breath for Disease Detection, https://doi.org/10.1146/annurev-anchem-071213-020043
* Dogs Are Teaching Machines to Sniff Out Cancer, https://www.the-scientist.com/news-opinion/dogs-are-teaching-machines-to-sniff-out-cancer-68469

