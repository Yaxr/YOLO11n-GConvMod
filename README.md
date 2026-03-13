# YOLO11n-GConvMod
YOLO11n-GConvMod is a face detection model that modifies YOLO11n by replacing the PSABlock with GConvMod, inspired by Conv2Former, to increase mAP50 and reduce GFLOPs.

| Journal | Model | Parameters (M) | FLOPs | mAP50 Easy | mAP50 Medium | mAP50 Hard |
|--------|------|---------------|------|-----------|-------------|-----------|
| **Ours** | YOLO11n GConvMod | 1.4 | 6.3G | 0.93 | 0.91 | 0.78 |
|  | YOLO11n Original | 2.5 | 6.4G | 0.93 | 0.91 | 0.77 |
|  | YOLO11s Original | 9.4 | 21.5G | 0.94 | 0.92 | 0.79 |
| **Chen et al., 2021** | YOLOv2 | - | - | 0.33 | 0.29 | 0.13 |
|  | YOLOv3 | - | - | 0.68 | 0.69 | 0.69 |
|  | YOLO-face–anchor | - | - | 0.78 | 0.73 | 0.47 |
|  | YOLO-face–GIoU | - | - | 0.74 | 0.70 | 0.47 |
|  | YOLO-face–darknet-53 | - | - | 0.82 | 0.77 | 0.52 |
|  | YOLO-face–deeperdarknet | - | - | 0.89 | 0.87 | 0.69 |
| **Qi et al., 2023** | YOLOv5n0.5 | 0.4 | 0.5G | 0.90 | 0.88 | 0.73 |
