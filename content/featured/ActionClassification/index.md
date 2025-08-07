---
date: '3'
title: 'Action Classification on Diving Sequence'
cover: './demo.png'
github: 'https://github.com/NamrataThakur/Action-Classification-on-Diving-Sequence'
#external: 'https://www.newline.co/courses/build-a-spotify-connected-app'
#cta: 'https://www.newline.co/courses/build-a-spotify-connected-app'
tech:
  - Video Processing
  - Action Recognition
  - Temporal Segmentation
  - CNN
  - i3D
  - Tensorflow 2
  - Flask
---

- Designed and developed a **Computer Vision (CV)** pipeline for **Action Quality Assessment (AQA)** on a dataset of 2K+ diving videos to predict performance scores for each sequence.
  <br>
  <br>
- Developed an ensemble architecture combining deep learning–based features (**number of twists** and **somersaults** extracted via **RepNet**) with hand-crafted features (**angle of entry, splash size**) to enhance output interpretability. Final score prediction was performed using an **SVM Regressor**, achieving an R² score of 0.81.
  <br>
  <br>
- Led the architecture design by incorporating robust **temporal modeling**, leveraging **2D CNNs** for temporal segmentation, **I3D** for spatio-temporal feature extraction and automated scoring, and **optical flow–based analysis** to quantify splash size dynamics.
  <br>
  <br>
- Temporal consistency across frames was further modeled to capture fine-grained motion patterns critical for action quality assessment.
