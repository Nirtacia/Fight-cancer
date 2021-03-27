# Identifying serious medical conditions at an early stage

Final project for the Building AI course

## Summary

Create systems/devices that analyze exhaled breath and thereby detecting medical conditions at an early stage. The devices are to be installed at workplaces, schools, stores etc. 

## Background

If you feel really ill and need help, you naturally seek medical attention. However: people suffering from a number of serious medical conditions, e.g. certain forms of cancer, don´t necessarily feel "ill" or understand that they are ill until it is already to late for them to get successful treatment. These people tend to die way too young. What if there was a way of predicting serious diseases long before you even suspect you have them?

## How is it used?

Measuring the composition of exhaled breath gives us a clue of the condition of our lungs, but can also be used to predict other serious diseases that we are yet unaware of. Therefore, devices that collect samples of exhaled breath are to be installed at public locations, such as schools, workplaces, stores, hospitals, trains, buses etc. When a person passes by, an exhaled breath sample is taken. At the same time, the person is identified using facial recognition, or when possible: a credit card or an ID card.

If the analysis of the exhaled breath sample indicates anything extraordinary, the individual in question is contacted and encouraged to seek medical attention. 

Describe the process of using the solution. In what kind situations is the solution needed (environment, time, etc.)? Who are the users, what kinds of needs should be taken into account?

Images will make your README look nice!
Once you upload an image to your repository, you can link link to it like this (replace the URL with file path, if you've uploaded an image to Github.)
![Cat](https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg)

If you need to resize images, you have to use an HTML tag, like this:
<img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg" width="300">

This is how you create code examples:
```
def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]

   totPop = sum(pop)
   totFish = sum(fishers)

   # write your solution here

   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%

main()
```


## Data sources and AI methods
Where does your data come from? Do you collect it yourself or do you use data collected by someone else?
If you need to use links, here's an example:
[Twitter API](https://developer.twitter.com/en/docs)

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

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
