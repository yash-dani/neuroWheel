# neuroWheel
Using a Mattel MindFlex Toy (EEG sensor) in order to create a mind controlled wheelchair 

## Project Description:
I'm using a cheap EEG sensor that came from the Mattel Mindflex boardgame to read brain-wave data. This will then undergo noise reduction via machine learning models. Then, a support vector machine will be used to determine if a person is thinking of moving forward, which will cause a wheelchair to start moving.

## Status Updates
Last updated: January 2020

### Updates:

#### Completed:
- rewired the circuitry in the EEG headset to allow it to connect to an arduino
- collected the arduino and successfully collected brainwave data
- used external libraries in order to graph brain wave data, which was then collecting to train a machine learning model

#### Currently working on:
- labelling the dataset in order to create a noise reducing machine learning model 
- researching the best way to classify data in a quick and efficienty manner 
- improving accuracy of EEG data 
