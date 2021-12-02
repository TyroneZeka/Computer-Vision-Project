# FACE MASK DETECTION SYSTEM

## Group Members : Mudonhi Henry, Zeka Tyrone, Mlambo Praise, Tshuma Methembe

## Problem Statement

With the world currently suffering from the covid 19, the health officials have been advocating for people to wear face masks as it has been proven to drastically reduce the spread of the virus. Other people have however been found refusing to wear face masks especially in schools and shopping centres. Our proposed system is for detecting people who go in public spaces without their face masks and this can also be used to fine people who do not want to wear face masks. 

## Approach
We propose to use a CNN model like ImageNet and train it to learn the difference between faces with a face mask and faces without a face mask. We propose to train the model until a decent accuracy has been achieved. The next step will be to detect the facial features in a given image, when the model is tested to a new face. Lastly we will apply the model to test the presence of a mask and then we deploy for public use. 

## Dataset
We propose to use the [COVID-19 images dataset](https://github.com/prajnasb/observations) by Prajna Bhandary for this project. The dataset contains 1376 images, with 690 images of people wearing face masks and 686 images of people not wearing face masks. We will be splitting the data into training and testing data. 

## Computational Resources
A laptop is sufficient to run the model. We are going to use python programming language since it is supported by many IDEs