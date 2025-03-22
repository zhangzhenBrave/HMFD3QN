# HMFD3QN
Code submission upon paper acceptance.

# AI Service Details

| Name                          | Type                 | w_s                  | Accuracy | Model Size (MB) | GFLOPs  | Input Size (MB) |
|-------------------------------|----------------------|----------------------|----------|------------------|---------|-----------------|
| ConvNeXt_Tiny                 | Image Classification | Continuous Services  | 82.52    | 28.6             | 4.46    | 0.57            |
| ConvNeXt_Small                | Image Classification | Continuous Services  | 83.616   | 50.2             | 8.68    | 0.57            |
| ConvNeXt_Base                 | Image Classification | Continuous Services  | 84.062   | 88.6             | 15.36   | 0.57            |
| ConvNeXt_Large                | Image Classification | Continuous Services  | 84.414   | 197.8            | 34.36   | 0.57            |
| DeepLabV3_MobileNet_V3        | Semantic Segmentation| Continuous Services  | 60.3     | 11.0             | 10.45   | 3.00            |
| DeepLabV3_ResNet101           | Semantic Segmentation| Continuous Services  | 67.4     | 61.0             | 258.74  | 3.00            |
| DeepLabV3_ResNet50            | Semantic Segmentation| Continuous Services  | 66.4     | 42.0             | 178.72  | 3.00            |
| RetinaNet_ResNet50_FPN_V2     | Object Detection     | Occasional Services  | 41.5     | 38.2             | 152.24  | 7.81            |
| RetinaNet_ResNet50_FPN        | Object Detection     | Occasional Services  | 36.4     | 34.0             | 151.54  | 7.81            |
| MaskRCNN_ResNet50_FPN_V2      | Instance Segmentation| Occasional Services  | 47.4     | 46.4             | 133.92  | 7.81            |
| MaskRCNN_ResNet50_FPN         | Instance Segmentation| Occasional Services  | 37.9     | 44.4             | 137.42  | 7.81            |
| MViT_V1_B                     | Video Classification | Continuous Services  | 78.477   | 36.6             | 70.6    | 19.66           |
| Swin3D_S                      | Video Classification | Continuous Services  | 79.521   | 49.8             | 82.84   | 19.66           |
| Swin3D_T                      | Video Classification | Continuous Services  | 77.715   | 28.2             | 43.88   | 19.66           |

**Note:**  
- The metrics in the table are sourced from [PyTorch Vision Models](https://pytorch.org/vision/stable/models.html?spm=5176.28103460.0.0.3bb45d27eKerum).
