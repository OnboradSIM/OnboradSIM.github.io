# OnboardSIM: Onboard Terrain Classification via Stacked Intelligent Metasurface-Diffractive Deep Neural Networks

This repository contains the project page for our paper accepted to the **3rd ML4RS Workshop at ICLR 2025**, April 27th 2025, Singapore. The paper presents a novel approach for onboard terrain classification from SAR level-0 raw data using stacked intelligent metasurfaces.

## Project Overview

Space-borne remote sensing missions increasingly rely on Synthetic Aperture Radar (SAR) data to support environmental and societal applications such as deforestation detection, flood monitoring, and agricultural assessment. However, the continuous growth in data volume poses significant challenges in terms of downlink bandwidth, energy consumption, and real-time processing.

Our research introduces a wave-based diffractive deep neural network (D²NN) framework that processes S1 level-0 raw IQ data in orbit, reducing the need for extensive data transmission and computing resources at terrestrial stations.

## Key Contributions

- **Multi-Layer Metasurface Inference:** We design a multi-layer SIM-based approach that performs layer-by-layer feature extraction in the electromagnetic domain, achieving higher representational capacity than single-layer systems.

- **Enhancement through Data Augmentation:** Our research indicates that omitting phase-rotation data augmentation results in a substantial decrease in the F1 Score (from 90.60% to 69.35%).

- **Real-World Terrain Classification:** We validate our model on actual S1 level-0 raw IQ data, achieving comprehensive performance levels around 90%.

## Project Structure

- `index.html`: Main project page
- `style.css`: Stylesheet for the project page
- `images/`: Contains figures and visualizations
- `README.md`: This file

## Running the Project Page Locally

To view the project page locally:

1. Clone this repository
2. Open `index.html` in your web browser

## Authors

- Mengbing Liu - Nanyang Technological University
- Xin Li - Nanyang Technological University
- Jiancheng An - Nanyang Technological University
- Chau Yuen - Nanyang Technological University

## Acknowledgments

This research received funding from the Agency for Science, Technology and Research (A*STAR), Singapore, under Grant No. M22L1b0110. It was also supported by the National Research Foundation, Singapore, and the Infocomm Media Development Authority under the Future Communications Research & Development Programme (FCP-NTU-RG-2024-025).

## Citation

```
@inproceedings{liu2025onboard,
    title={Onboard Terrain Classification via Stacked Intelligent Metasurface-Diffractive Deep Neural Networks from SAR Level-0 Raw Data},
    author={Liu, Mengbing and Li, Xin and An, Jiancheng and Yuen, Chau},
    booktitle={3rd Machine Learning for Remote Sensing Workshop at ICLR},
    year={2025}
}
``` 