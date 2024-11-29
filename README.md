# "Mental Stress Classification Based Single nad Continuous cycle ECG Feature Fusion Ensemble Model"

#### by- Jihun Lee


+ ***Ms Student, Dept. of IT Fusion Technology***  
+ ***Chosun University, Gwangju, Rep. of Korea***


## Task- At A Glance:
Through the feature fusion CNN-LSTM model, single and continuous-cycle ECG feature are extracted and fused to diagnose mental stress.  
1. __Task__: Diagnosis mental stress
2. __Input__: ECG Signal (single and continuous-cycle)
3. __Output__:  4 Class (Stress and other)
4. __Database__: 2, (1) _WESAD_, (2) _MAUS_
5. __Preprocessing__: Butterworth filter denoising, Normalization, Segmentation
6. __Fusion method__: Max
7. __Result__: WESAD - **99.62%** (4 class), MAUS - **96.59%** (4 class)


## Publication
TBD

#### Abstract


## Requirements
Use the "requirements.txt" file.

## Feature Fusion CNN-LSTM Overview
+ Split into single and continuous-cycle ECG to identify fast and consecutive waveform changes in stressful situations
+ Feature Fusion CNN-LSTM analyzes ECG from multiple perspectives
+ Multi-database experiments validate high and consistent performance
+ Can be used for real-time stress diagnosis

![workflow](https://github.com/eejji/ECG-Feature-Fusion-CNN-LSTM/blob/main/Image/Workflow.jpg)


## Database
In this study, we use two public available database.

+ __WESAD__ Database : [Available](https://archive.ics.uci.edu/dataset/465/wesad+wearable+stress+and+affect+detection), [scholar google](https://dl.acm.org/doi/abs/10.1145/3242969.3242985)
+ __MAUS__ Ddatabase : [Available](https://ieee-dataport.org/open-access/maus-dataset-mental-workload-assessment-n-back-task-using-wearable-sensor), [scholar google](https://arxiv.org/abs/2111.02561)


## Datapreprocssing
![pre](https://github.com/eejji/ECG-Feature-Fusion-CNN-LSTM/blob/main/Image/Preprocessed_ECG.jpg)

## ECG Signal Segmentation
![seg](https://github.com/eejji/ECG-Feature-Fusion-CNN-LSTM/blob/main/Image/ECG_segmentation_process.jpg)

## Model Architecture
![model](https://github.com/eejji/ECG-Feature-Fusion-CNN-LSTM/blob/main/Image/Feature_Fusion_Model.jpg)

