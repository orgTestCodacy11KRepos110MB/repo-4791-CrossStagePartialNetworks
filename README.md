# Cross Stage Partial Networks
This is the implementation of "[CSPNet: A New Backbone that can Enhance Learning Capability of CNN](https://arxiv.org/abs/1911.11929)" using Pytorch framwork.

![](https://github.com/WongKinYiu/CrossStagePartialNetworks/blob/master/fig/cmp.png)

For installing Pytorch YOLOv3, you can refer to [YOLOv3(ultralytics)](https://github.com/ultralytics/yolov3).

This branch shows the results train **CSPNet** from scratch using Pytorch.

# MS COCO

| Model | Size | 1080ti *fps* |  AP  | AP50 | AP75 | APS | APM | APL | RS  | RM  | RL  |
| :---- | :--: | :----------: | :--: | :--: | :--: | :-: | :-: | :-: | :-: | :-: | :-: |
| **CSPNet-PANet-SPP** | 416×416 | 238 | 26.5 | 44.8 | 27.0 | 8.2 | 28.0 | 38.4 | 15.5 | 43.0 | 56.6 |

# Acknowledgements
[https://github.com/AlexeyAB/darknet](https://github.com/AlexeyAB/darknet)

[https://github.com/ultralytics/yolov3](https://github.com/ultralytics/yolov3)
