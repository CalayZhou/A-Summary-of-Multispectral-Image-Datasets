# A Summary of Multispectral (RGBT) Image Datasets


This document lists publicly available multispectral (RGBT) image datasets across multiple vision tasks (e.g., image fusion, object detection, segmentation, tracking). 

***

##  1. Image Fusion & Matching

| # | Name                                                                  | Year | Type  | Samples | Scene          | Publication        |
| - | --------------------------------------------------------------------- | ---- | ----- | ------- | -------------- | ------------------ |
| 1 | multispectraldata | 2021 | Video | 53      | Indoor/Outdoor |  multi-spectral dataset for evaluating motion es-timation systems. In 2021 IEEE International Conference on Robotics and Automation (ICRA), pages 5560–5566. IEEE, 2021.               |
| 2 | CVC-15                                                                | 2016 | Image | 100     | Urban          | Cvc-15 multimodal stereo dataset. http://adas.cvc.uab.es/elektra/enigma-portfolio / cvc - 15 - multimodal - stereo -dataset-2/, 2016.                  |
| 3 | CVC-lghd                                                              | 2015 | Image | 44      | Driving        |Lghd: A feature descriptor for matching across non-linear intensity variations. In Image Processing (ICIP), 2015 IEEE International Conference on, page 5. IEEE, 2015. 3             |
| 4 | RoadScene                                                             | 2020 | Image | 221     | Driving        | Fusiondn: A unified densely connected network for image fusion. In proceedings of the Thirty-Fourth AAAI Con-ference on Artificial Intelligence, 2020. 3           |
| 5 | MSRS                                                                  | 2022 | Image | 1444    | Driving        | Piafusion: A progressive infrared and visible im-age fusion network based on illumination aware. Information Fusion, 2022.  |
| 6 | TNO                                                                   | 2014 | Image | 60      | Military       | The tno multiband image data collection. Data in brief, 15:249–251, 2017.         |
| 7 | CATS                                                                  | 2017 | Image | 1400    | Indoor/Outdoor | Cats: A color and ther-mal stereo benchmark. In Proceedings of the IEEE Con-ference on Computer Vision and Pattern Recognition, pages 2961–2969, 2017.               |
| 8 | M³FD                                                                  | 2022 | Image | 4200    | Overcast       | Target-aware dual adversarial learning and a multi-scenario multi-modality benchmark to fuse infrared and visible for object detection. In Proceedings of the IEEE/CVF conference on computer vi-sion and pattern recognition, pages 5802–5811, 2022.              |
| 9 | MTV                                                               | 2022 | Image |  40,644     |Outdoor      | "A multi-view thermal–visible image dataset for cross-spectral matching." Remote Sensing 15.1 (2022): 174.              |
***

## 2. Object Detection

| #  | Name         | Year | Type  | Samples          | Scene          | Publication |
| -- | ------------ | ---- | ----- | ---------------- | -------------- | ----------- |
| 1  | VEDAI        | 2016 | Image | 1210             | Aerial         | Vehicle detec-tion in aerial imagery (vedai): a benchmark. Technical re-port, Tech. Rep., 2015.          |
| 2 | KAIST        | 2015 | Video | 95k              | Driving        | Multispectral pedestrian detection: Benchmark dataset and baseline. In Proceedings of the IEEE conference on computer vision and pattern recogni-tion, pages 1037–1045, 2015.         |
| 3 | LLVIP        | 2021 | Image | 15448            | Surveillance   | Llvip: A visible-infrared paired dataset for low-light vision. In Proceedings of the IEEE/CVF international con-ference on computer vision, pages 3496–3504, 2021.       |
| 4 | MFNet        | 2021 | Image | 1569             | Driving        | Mfnet: Towards real-time se-mantic segmentation for autonomous vehicles with multi-spectral scenes. In 2017 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), pages 5108–5115. IEEE, 2017.         |
| 5 | FLIR         | 2018 | Image | 10228            | Driving        | https://oem.flir.com/zh-cn/solutions/automotive/adas-dataset-form/     |
| 6 | CVC14        | 2016 | Image | 8518             | Pedestrian     | Pedestrian detection at day/night time with visible and fir cameras: A comparison. Sensors, 16(6):820, 2016.        |
| 7 | MAVD         | 2021 | Image | 113282           | Driving        | There is more than meets the eye: Self-supervised multi-object detection and tracking with sound by distilling multimodal knowledge. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, pages 11612–11621, 2021.         |
| 8 | DroneVehicle | 2022 | Image | 28439            | Drone          | Drone based rgbt vehicle detection and count-ing: A challenge. arXiv e-prints, pages arXiv–2003, 2020.       |
| 9 | SMOD         | 2024 | Image | 8676             | Driving        | Amfd: Distillation via adaptive mul-timodal fusion for multispectral pedestrian detection, 2024.       |
| 10 | DVTOD        | 2023 | Image | 4358             | Indoor/Outdoor | Misaligned visible-thermal object detection: A drone-based benchmark and baseline. IEEE Transactions on Intelligent Vehicles, 2024.         |
| 11 | RGBT-Tiny    | 2024 | Video | 93k (115 videos) | Indoor/Outdoor | Visible-thermal tiny object detection: A benchmark dataset and baselines. arXiv preprint arXiv:2406.14482, 2024.        |
| 12 | VEDAI   | 2016 | Image | 1200 | Outdoor | "Vehicle detection in aerial imagery: A small target detection benchmark." Journal of Visual Communication and Image Representation 34 (2016): 187-203.        |

***

 

## 3. Semantic Segmentation

| #  | Name             | Year | Type  | Samples          | Scene        | Publication    |
| -- | ---------------- | ---- | ----- | ---------------- | ------------ | -------------- |
| 1 | PST900           | 2020 | Image | 894              | Subterranean | Pst900: Rgb-thermal calibration, dataset and segmentation network. In 2020 IEEE international conference on robotics and au-tomation (ICRA), pages 9441–9447. IEEE, 2020.           |
| 2 | Freiburg Thermal | 2020 | Image | 20647            | Outdoor      | Heatnet: Bridging the day-night domain gap in semantic segmenta-tion with thermal images. In 2020 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), pages 8461–8468. IEEE, 2020.           |
| 3 | RoadScene-seg    | 2022 | Image | 1326             | Road Scene   | Ccaffmnet: Dual-spectral semantic segmentation network with channel-coordinate attention feature fusion module. Neurocomput-ing, 482:236–251, 2022.  |
| 4 | SemanticRT       | 2023 | Image | 11371            | Urban        | Semanticrt: A large-scale dataset and method for robust semantic segmentation in multispectral images. In Proceedings of the 31st ACM International Conference on Multimedia, pages 3307–3316, 2023.          |
| 5 | MVSeg            | 2023 | Video | 53k (738 videos) | Driving      | Multispectral video se-mantic segmentation: A benchmark dataset and baseline. In Proceedings of the IEEE/CVF Conference on Computer Vi-sion and Pattern Recognition, pages 1094–1104, 2023.           |
| 6 | FMB              | 2023 | Image | 1500             | Driving      | Multi-interactive feature learning and a full-time multi-modality benchmark for image fusion and segmentation. In Proceed-ings of the IEEE/CVF international conference on computer vision, pages 8115–8124, 2023.           |

***

## 4. Salient Object Detection

| #  | Name           | Year | Type  | Samples | Scene          | Publication |
| -- | -------------- | ---- | ----- | ------- | -------------- | ----------- |
| 1 | VT821          | 2017 | Image | 821     | Indoor/Outdoor | A unified rgb-t saliency detec-tion benchmark: dataset, baselines, analysis and a novel ap-proach. arXiv preprint arXiv:1701.02829, 2017.         |
| 2 | VT1000         | 2020 | Image | 1000    | Indoor/Outdoor | Rgb-t image saliency detection via collaborative graph learning. IEEE Transactions on Multi-media, 22(1):160–173, 2019.         |
| 3 | VT5000         | 2022 | Image | 5000    | Indoor/Outdoor | Rgbt salient object detection: A large-scale dataset and benchmark. IEEE Transactions on Multi-media, 25:4163–4176, 2022.          |
| 4 | VI-RGBT1500    | 2022 | Image | 1500    | Indoor/Outdoor | Multiple graph affinity interactive network and a variable il-lumination dataset for rgbt image salient object detection. IEEE Transactions on Circuits and Systems for Video Tech-nology, 33(7):3104–3118, 2022.        |
| 5 | UAV RGB-T 2400 | 2023 | Image | 2400    | Drone          | Modality registration and ob-ject search framework for uav-based unregistered rgb-t im-age salient object detection. IEEE Transactions on Geo-science and Remote Sensing, 61:1–15, 2023.        |

***



## 5. Crowd Counting

| #  | Name      | Year | Type  | Samples | Scene          | Publication |
| -- | --------- | ---- | ----- | ------- | -------------- | ----------- |
| 1 | RGBT-CC   | 2021 | Image | 2030    | Indoor/Outdoor | Cross-modal collaborative represen-tation learning and a large-scale rgbt benchmark for crowd counting. In Proceedings of the IEEE/CVF conference on computer vision and pattern recognition, pages 4823–4833, 2021.         |
| 2 | DroneRGBT | 2020 | Image | 3600    | Drone          | Rgb-t crowd counting from drone: A benchmark and mmccn network. In Proceed-ings of the Asian conference on computer vision, 2020.         |

***




## 6. Object Tracking

| #  | Name    | Year | Type  | Samples              | Scene              | Publication         |
| -- | ------- | ---- | ----- | -------------------- | ------------------ | ------------------- |
| 1 | VT-MOT  | 2024 | Video | 401k (582 videos)    | Surveillance/Drone | Visible-thermal multiple object tracking: Large-scale video dataset and progressive fusion approach, 2024.                |
| 2 | VTUAV   | 2022 | Video | 1.7M (500 videos)    | Tracking           | Visible-thermal uav tracking: A large-scale benchmark and new baseline. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, pages 8886–8895, 2022.                |
| 3 | RGBT234 | 2019 | Video | 116.7k (234 videos)  | Tracking           | Rgb-t object tracking: Benchmark and baseline. Pat-tern Recognition, 96:106977, 2019.  |
| 4 | LasHeR  | 2021 | Video | 738.8k (1224 videos) | Tracking           | Lasher: A large-scale high-diversity benchmark for rgbt tracking. IEEE Transactions on Image Processing, 31:392–404, 2021.                 |
| 5 | GTOT    | 2016 | Video | 50 videos            | Tracking           | Learning collaborative sparse representation for grayscale-thermal tracking. IEEE Transactions on Image Processing, 25(12):5743–5756, 2016.                 |
| 6| RGBT210 | 2017 | Video | 210 videos           | Tracking           | Weighted sparse representation regularized graph learning for rgb-t object tracking. In Proceedings of the 25th ACM international conference on Multimedia, pages 1856–1864, 2017.             |
| 7| NOT-156 | 2025 | Video | 156 videos           | Tracking           | "NOT-156: Night Object Tracking using Low-light and Thermal Infrared: From Multi-modal Common-aperture Camera to Benchmark Datasets." IEEE Transactions on Geoscience and Remote Sensing (2025).          |



***

##  7. Depth Estimation
| #  | Name        | Year | Type  | Samples           | Scene          | Publication |
| -- | ----------- | ---- | ----- | ----------------- | -------------- | ----------- |
| 1 | Multi-Spectral Stereo (MS2)       | 2023 | Video |  195K               | Outdoor | Deep depth estimation from thermal image. Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition. 2023.      |
| 2 | ViViD   | 2019 | Video |  14              | Indoor/Outdoor |  “ViViD : Vision for Visibility Dataset,” in ICRA Workshop on Dataset Generation and Benchmarking of SLAM Algorithms for Robotics and VR/AR, Montreal, May. 2019    |


##  Other Tasks

| #  | Name        | Year | Type  | Samples           | Scene          | Publication |
| -- | ----------- | ---- | ----- | ----------------- | -------------- | ----------- |
| 1 | VITLD       | 2022 | Image | 880               | Indoor/Outdoor | Multilevel atten-tion imitation knowledge distillation for rgb-thermal trans-mission line detection. Expert Systems with Applications, 260:125406, 2025.          |
| 2 | RGB-T-Glass | 2022 | Image | 5551              | Indoor/Outdoor | Glass segmentation with rgb-thermal image pairs. IEEE Transactions on Image Processing, 32:1911–1926, 2023.         |
| 3 | IRVI        | 2020 | Video | 24352 (12 videos) | Monitoring     | I2v-gan: Unpaired infrared-to-visible video translation. In Proceedings of the 29th ACM international conference on multimedia, pages 3061–3069, 2021.      |

***
