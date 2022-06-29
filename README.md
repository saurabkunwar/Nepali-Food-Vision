# Nepali Food Vision

This a simple model that classifies various classes of nepali food based on their picture. First challenge of this project was to find the dataset. Unfortunately I could not find any
dataset that consists of Nepali food. So, I scraped google and created simple dataset consisting of 9 classes. I have made this data public in Kaggle. 

https://www.kaggle.com/datasets/saurabkunwar/nepali-food-images

## Motivation

When going through tensorflow deep learning course taught by Daniel Bourke, I stumbled upon project called FoodVision. After completing that project, I wanted to make similar one
but with Nepali cuisines. I could not find any dataset. So, I decided to scrap google and create my own dataset. Then I experimented with various custom model as well as
fine tuned existing model using Tensorflow.

## Technical Aspect

1. Used tensorflow for custom convolutional models and data augmentation
2. Finetuned efficientnetb0.

Finetuning upper 20 layers of efficientnetb0 yielded 93% of validation accuracy with only 80-300 training samples.

## Food Categories

1. Chatamari
2. Chhoila
3. Dalbhat
4. Dhindo
5. Gundruk
6. Kheer
7. Momo
8. Sekuwa
9. Selroti

## Futher improvements

1. More images should be collected for each food class.
2. More image classes can be added.
3. Web app with recepie of food
