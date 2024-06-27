# HistRoadSegformer

| Experiment No  |       Model       | Optimizer   |  Loss  | Augmentation   |  Batch Size  |  Precision  |   Recall  |  F1 Score  |   IoU  |  Weights  |
|:--------------:|:-----------------:|:-----------:|:------:|:--------------:|:------------:|:-----------:|:---------:|:----------:|:------:|:---------:|
|     Exp-1      |    SegFormer-B0   |    Adam     |  Dice  |      Old       |      16      |    0.6031   |   0.7043  |    0.6490  | 0.4807 |           |
|     Exp-2      |    SegFormer-B0   |    Adam     |  Focal |      Old       |      16      |    0.6876   |   0.5579  |    0.6158  | 0.4455 |           |
|     Exp-3      |    SegFormer-B0   |   AdamW     |  Focal |      Old       |      16      |    0.6605   |   0.5932  |    0.6242  | 0.4547 |           |
|     Exp-4      |    SegFormer-B0   |   AdamW     |  Focal |      No        |      16      |    0.6751   |   0.6780  |    0.6756  | 0.5110 |           |
|     Exp-5      |    SegFormer-B0   |    Adam     |  Dice  |      New       |      16      |    0.6293   |   0.7203  |    0.6697  | 0.5053 |           |
|     Exp-6      |    SegFormer-B0   |   AdamW     |  Focal |      New       |      16      |    0.7057   |   0.6675  |    0.6853  | 0.5216 |           |
|     Exp-7      |    SegFormer-B0   |   AdamW     |  Dice  |      New       |      16      |    0.6668   |   0.6901  |    0.6780  | 0.5136 |           |
|     Exp-8      |    SegFormer-B0   |    Adam     |  Focal |      New       |      16      |    0.6966   |   0.6831  |    0.6889  | 0.5259 |           |
|     Exp-9      |    SegFormer-B0   |   AdamW     |  Focal |      New       |       8      |    0.7015   |   0.6434  |    0.6717  | 0.5067 |           |
|    Exp-10      |    SegFormer-B1   |   AdamW     |  Focal |      New       |      16      |    0.6928   |   0.6886  |    0.6905  | 0.5279 |           |
|    Exp-11      |    SegFormer-B1   |    Adam     |  Focal |      New       |      16      |    0.6822   |   0.6956  |    0.6878  | 0.5251 |           |
|    Exp-12      |    SegFormer-B1   |   AdamW     |  Focal |      New       |       8      |    0.6842   |   0.6485  |    0.6632  | 0.4988 |           |
|    Exp-13      |    SegFormer-B2   |   AdamW     |  Focal |      New       |       8      |    0.6893   |   0.6960  |    0.6920  | 0.5297 |           |
|    Exp-14      |    SegFormer-B2   |    Adam     |  Focal |      New       |       8      |    0.7061   |   0.6974  |    0.7017  | 0.5411 |           |
|    Exp-15      |  Unet++ TIMM [2]  |    Adam     |  Dice  |      Old       |      16      |    0.5141   |   0.6970  |    0.5772  | 0.4199 |           |
