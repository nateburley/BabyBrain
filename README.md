# Baby Brain

## Summary
Infant mood detection with a Muse S EEG headset and deep learning.

## Purpose
To new parents, infants are "an enigma wrapped in a mystery inside an enigma", to quote Churchill. They fuss and cry, and you have no idea what they want.
Are they hungry? Tired? Do they need a new diaper? No one knows! In this project, we will attempt to build a simple program that streams data in real-time 
from the Muse S headset, and classifies what your baby needs based on their brain waves.

## Past Work
TODO

## Setup
### Required Hardware
- NVIDIA Jetson Nano
- Muse S EEG Headset

### Software
#### EEG Data Collection
Data can be collected via this app:
- <a href="https://mind-monitor.com/">Mind Monitor App</a>

Or alternately, with this open-source tool:
- <a href="https://github.com/alexandrebarachant/muse-lsl">Muse LSL</a>

#### EEG Data Classification With Deep Learning
##### Data
For a list of possible datasets to use to train a model in place of collecting your own data, I recommend the following compilation:
- <a href="https://github.com/meagmohit/EEG-Datasets">meagmohit: All Open-Source EEG Datasets</a>

I will be using this dataset from Kaggle:
- <a href="https://www.kaggle.com/datasets/birdy654/eeg-brainwave-dataset-feeling-emotions">EEG Brainwave Dataset: Feeling Emotions</a>

##### Model
TODO

## Procedure
Slightly unintuitively (due to a delay in being able to get an EEG headset) this project will "work backwards", starting with constructing a model to 
classify EEG data, and then moving on to collecting data and performing real-time inference with the Muse S EEG headset.

### Part 1: Classifying EEG Data
TODO

### Part 2: Collecting Real-World Data From A Baby
TODO

### Part 3: Performing Online Inference on a Real Baby
TODO
