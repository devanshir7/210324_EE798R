# 210324_EE798R
# SPEECH EMOTION RECOGNITION WITH GLOBAL-AWARE FUSION ON MULTI-SCALE FEATURE REPRESENTATION
Authors: Wenjing Zhu, Xiang Li

## Phase 1
## Code
1. Github Repo Link (Containing all scripts): https://github.com/devanshir7/GLAM


## Instructions

## Preprocess

 1. Specify the path of IEMOCAP corpus in `path.py`
 2. Run `python handleIEMOCAP.py` to rename audio filenames.
 3. Run `python seeds.py` to generate seeds.

## Training

 1. Use python train.py to train a new model.

 2. Run directly: ./run(to make the script executable: chmod +x run) or bash run.

## Phase 2
## Code
1. Github Repo Link (Containing all scripts): https://github.com/devanshir21/GLAM



## Instructions

## Preprocess

 1. Specify the path of IEMOCAP corpus in `path.py`
 2. Run `python handleIEMOCAP.py` to rename audio filenames.
 3. Run `python seeds.py` to generate seeds.

## Training

 1. Change the default feature extraction method to 'melspectrogram' in `train.py`
 2. Use python `train.py` to train a new model.
 3. Run directly: ./run(to make the script executable: chmod +x run) or bash run.


