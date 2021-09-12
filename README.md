# Street Traffic Tracking Source Code

This repository contains the code used for the street detection analytics project. It contains the code to both train and retrain the model used for prediction and to perform prediction on a given input.

This repository consists of two submodules, each with a different function. Going into each submodule will redirect to another repository with a specific README on how to run the code:
- darknet: This module can train a model on input data. I used this module to generate model weights that will recognize vehicles and pedestrians in different images
- deepsort: This module can track objects in a video given a weights file generated in the darknet module. I adapted this module as part of the web app, where a user can upload a video and then view the video with street objects tracked.

## Sources

https://github.com/AlexeyAB/darknet

https://github.com/theAIGuysCode/yolov4-deepsort
