# Multi-Target-Behavior-Detection-Dataset
├── data/                           # 数据集文件
│   ├── train/                      # 训练集
│   │   ├── images/                 # 训练图像
│   │   └── labels/                 # YOLO格式训练标签
│   └── val/                        # 验证集
│       ├── images/                 # 验证图像
│       └── labels/                 # YOLO格式验证标签
├── benchmark_results/              # 基准测试结果
│   ├── metrics/                    # 评估指标（mAP、Precision、Recall等）
│   ├── models/                     # 基线模型权重文件
│   └── visualize/                  # 检测结果可视化示例
├── configs/                        # 配置文件
│   ├── dataset.yaml                # 数据集路径与类别配置
│   └── model_configs/              # 模型结构配置文件（如yolov8n.yaml）
└── scripts/                        # 实用脚本
    ├── evaluate.py                 # 模型评估脚本
    └── visualize.py                # 结果可视化脚本
