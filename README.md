This repository contains the material for the workshop ["AIM347 - Time-series prediction using GluonTS and Amazon SageMaker"](https://www.portal.reinvent.awsevents.com/connect/sessionDetail.ww?SESSION_ID=98535).

[Part 1](notebooks/part1/Intro_to_gluonts.ipynb) gives a brief overview of basic GluonTS components.

### Lab 1
Tutorial [part 2](notebooks/part2/descriptive_stats.ipynb) is optional. It gives a high level overview of the time-series modeling pipeline and you will get more familiar with the dataset.

In [part 3](notebooks/part3/twitter_volume_forecast.ipynb), you will learn how to run a time-series forecast using GluonTS. You will create a baseline with a seasonal naive predictor and train a DeepAR model.

### Lab 2
In [part 4](notebooks/part4/twitter_volume_sagemaker.ipynb) you will use Amazon SageMaker to train and tune your DeepAR model. You will use SageMaker automatic model tuner to find better hyperpameters and then deploy the tuned model as an endpoint.
