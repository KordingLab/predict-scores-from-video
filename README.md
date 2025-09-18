# Predicting scores from video

🚧 Currently undergoing revisions 🚧
|   | Run |
| - | --- | 
| Pose Estimation | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/quietscientist/gma_score_prediction_from_video/blob/main/0_PoseEstimation.ipynb) | 
| Feature Computation | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/quietscientist/gma_score_prediction_from_video/blob/main/1_ProcessDetections.ipynb) | 
| Risk Prediciton | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/quietscientist/gma_score_prediction_from_video/HEAD)| 

Pose estimation code adapted from: [Open MMLab: MMPose](https://github.com/open-mmlab/mmpose)  
Feature computation code adapted from: [Chambers et al 2020](https://github.com/cchamber/Infant_movement_assessment)  
Score prediction code adapted from: [auto-sklearn](https://github.com/automl/auto-sklearn)

Pipeline for predicting any score (e.g., clinical scores, sports performance scores) or other relevant variable from videos of moving humans of any age. Repository comprises:

1) Pose estimation
2) General timeseries pre-processing
3) General kinematic feature computation
4) Implementation of AutoSklearn 

Reference: [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.14042732.svg)](https://doi.org/10.5281/zenodo.14042732)

