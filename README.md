# Emotion and other facial attributes contributing to attractiveness

## About

Mini project for SC1015 (Introduction to Data Science and Artificial Intelligence) 

## Problem Definition

What are the facial attributes in addition to emotion that can boost attractiveness when setting online dating profile picture? 

## Motivation

According to a research paper published by the American Psychological Association in 2018, attractiveness generally had a strong influence on emotion perception. Tinder is an online dating platform that is the most widely used in Singapore. Tinder "Swipe Left, Swipe Right" feature encourages users to spend a few seconds identifying the "attractiveness" of the person's profile picture. 

Therefore, we believe that emotion perception might influence attractiveness when setting dating profile.

## Contributors

- @johnny-psh 
- @habzs 
- @SamsonOngqx 

## Dataset

Facial Expression Recognition (FER) 2013 <https://www.kaggle.com/datasets/msambare/fer2013>
CelebA <https://mmlab.ie.cuhk.edu.hk/projects/CelebA.html>

A small sample of both dataset are in this repo due to size constraints.

## Model Summary

Built 3 Convolutional Neural Network from scratch across 4 experiments with different hyperparameter tuning and training methods. 

## Conclusion

Emotion does not contribute to attractiveness during the small time frame. However, positive emotion such as smilling can still contribute to attractiveness during long periods of interaction. Provided a guideline for taking profile pictures for online dating profile based on data driven insights.

## Lesson Learnt

- Building a CNN from scratch using PyTorch
- Image cleaning and EDA
- Techniques to prevent overfitting
- Loading Image from other source to the model
- Nominal Categorical Variables Correlation 
- Google Colab and Github to collaborate

## Reference
- <https://doi.apa.org/doiLanding?doi=10.1037%2Femo0000513>
- <https://www.statista.com/statistics/1187795/singapore-leading-mobile-dating-apps/>
- <https://www.kaggle.com/datasets/msambare/fer2013>
- <https://mmlab.ie.cuhk.edu.hk/projects/CelebA.html>
- <https://en.wikipedia.org/wiki/Perceptual_hashing>
- <https://en.wikipedia.org/wiki/Hamming_distance>
- <https://towardsdatascience.com/a-comprehensive-guide-to-convolutional-neural-networks-the-eli5-way-3bd2b1164a53>
- <https://towardsdatascience.com/deep-learning-3-more-on-cnns-handling-overfitting-2bd5d99abe5d>
- <https://en.wikipedia.org/wiki/Cram%C3%A9r%27s_V>
- <https://scikit-learn.org/stable/modules/cross_validation.html>



