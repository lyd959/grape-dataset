# Grape-YOLO Dataset

**Paper title:** Grape-YOLO: A Scale-Preserving Lightweight Detector with Selective Compression and Multi-Scale Knowledge Distillation for Grape Cluster and Stem Detection

## Abstract

Reliable detection of grape clusters and stems is important for vision-based automated harvesting, yet grape stems are small, slender, and frequently occluded, making them vulnerable to feature loss during network compression and downsampling. Here, we propose Grape-YOLO, a lightweight detector that preserves the P3–P5 detection hierarchy of YOLO11n while selectively compressing the high-level P5 pathway. SCDown and C3Ghost are introduced to reduce computational redundancy, while multi-scale knowledge distillation from a frozen YOLO11s teacher is used to recover task-relevant representations across P3–P5. A vineyard dataset containing 2,225 images and 11,531 annotated grape-cluster and grape-stem instances was used for evaluation. Compared with YOLO11n, Grape-YOLO reduced the number of parameters and model size by 20.2% and 18.8%, respectively, while maintaining an mAP@50 of 0.638. For grape-stem detection, it achieved a precision of 0.681, recall of 0.476, AP@50 of 0.542, and AP@50:95 of 0.263. The grape-stem AP@50:95 was comparable to that of the YOLO11s teacher, despite using 78.1% fewer parameters. These results show that selective high-level feature compression combined with multi-scale knowledge distillation can reduce model complexity while retaining fine-scale representations relevant to grape-stem detection, supporting efficient visual perception for automated harvesting.

## Dataset

- Images: 2,225
- Annotated instances: 11,531
- Categories: grape clusters and grape stems
- Archive: `dataset.rar`
