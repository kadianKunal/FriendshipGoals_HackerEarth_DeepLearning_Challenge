# FriendshipGoals_HackerEarth_DeepLearning_Challenge

This repository contains solution to HackerEarth Deep Learning Challenge titled Friendship Goals. 

## The task is to build a Deep Learning model that analyzes an image of a gathering among friends and classifies them into groups of toddlers, teenagers, or adults.

Competition page: https://www.hackerearth.com/challenges/competitive/hackerearth-deep-learning-challenge-friendship-day/?utm_source=challenges-modern&utm_campaign=participated-challenges&utm_medium=right-panel

Dataset: https://www.kaggle.com/bing101/friendshipgoals/download

leadeboard : https://www.hackerearth.com/challenges/competitive/hackerearth-deep-learning-challenge-friendship-day/leaderboard/friendship-goals-4-8aa488d0/


## I have achieved rank 24/5494 with the following approach

I have implemented a Transfer learning model with ResNet50_v2 as base model

Used data augmentation techniques

Experimented with additonal layers over base model, learning rates, batch size, dropout percentage 

Fine-tuned last few layers of base model to further enhance the peroformance and accuracy.

Finally predicted the classes for test images and did a small analysis on the result.
