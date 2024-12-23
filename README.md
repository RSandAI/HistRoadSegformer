# Land Use and Land Cover Mapping Using Deep Learning Based Segmentation Approaches and VHR Worldview-3 Images
This repository contains the code for the paper [Automatic Road Extraction from Historical Maps Using Transformer-Based SegFormers](https://www.mdpi.com/2220-9964/13/12/464)



| Experiment No  |       Model       | Optimizer   |  Loss  | Augmentation   |  Batch Size  |  Precision  |   Recall  |  F1 Score  |   IoU  |  Weights  |
|:--------------:|:-----------------:|:-----------:|:------:|:--------------:|:------------:|:-----------:|:---------:|:----------:|:------:|:---------:|
|     Exp-1      |    SegFormer-B0   |    Adam     |  Dice  |      Old       |      16      |    0.6031   |   0.7043  |    0.6490  | 0.4807 | [Download](https://drive.google.com/file/d/1kGyaS1mYwsMZoop0rLMZrYLVZhOQbf53/view?usp=sharing)|
|     Exp-2      |    SegFormer-B0   |    Adam     |  Focal |      Old       |      16      |    0.6876   |   0.5579  |    0.6158  | 0.4455 | [Download](https://drive.google.com/file/d/1hGvj3WeG86YW45F__9b9_9dfijBHkkS7/view?usp=sharing)|
|     Exp-3      |    SegFormer-B0   |   AdamW     |  Focal |      Old       |      16      |    0.6605   |   0.5932  |    0.6242  | 0.4547 | [Download](https://drive.google.com/file/d/1YAKRhm2yk9MJ4dzGJQuyaxMMbkM17Mzw/view?usp=sharing)|
|     Exp-4      |    SegFormer-B0   |   AdamW     |  Focal |      No        |      16      |    0.6751   |   0.6780  |    0.6756  | 0.5110 | [Download](https://drive.google.com/file/d/1wom2dvOfiqdTH6CCnP94CiGq87ZmfacY/view?usp=sharing)|
|     Exp-5      |    SegFormer-B0   |    Adam     |  Dice  |      New       |      16      |    0.6293   |   0.7203  |    0.6697  | 0.5053 | [Download](https://drive.google.com/file/d/1l1wKY53ZPs0zwGYWhyRWy9Nkrt-vzWOF/view?usp=sharing)|
|     Exp-6      |    SegFormer-B0   |   AdamW     |  Focal |      New       |      16      |    0.7057   |   0.6675  |    0.6853  | 0.5216 | [Download](https://drive.google.com/file/d/1mviJYHOvYNcN5DjLgptrXz_zKVVBgdKU/view?usp=sharing)|
|     Exp-7      |    SegFormer-B0   |   AdamW     |  Dice  |      New       |      16      |    0.6668   |   0.6901  |    0.6780  | 0.5136 | [Download](https://drive.google.com/file/d/17580lyBjPzWm5xl_ai9A3zqZ-kixyA2a/view?usp=sharing)|
|     Exp-8      |    SegFormer-B0   |    Adam     |  Focal |      New       |      16      |    0.6966   |   0.6831  |    0.6889  | 0.5259 | [Download](https://drive.google.com/file/d/1fPcXRnwVP74-6RX0L7m9AOlruJHHQZ4N/view?usp=sharing)|
|     Exp-9      |    SegFormer-B0   |   AdamW     |  Focal |      New       |       8      |    0.7015   |   0.6434  |    0.6717  | 0.5067 | [Download](https://drive.google.com/file/d/1c4laoVCApKi2jjNMkBzQvQT-z5xgaDjr/view?usp=sharing)|
|    Exp-10      |    SegFormer-B1   |   AdamW     |  Focal |      New       |      16      |    0.6928   |   0.6886  |    0.6905  | 0.5279 | [Download](https://drive.google.com/file/d/1MuKlt5RXcX-x7fq9JNeVfH3UZm7BiZOu/view?usp=sharing)|
|    Exp-11      |    SegFormer-B1   |    Adam     |  Focal |      New       |      16      |    0.6822   |   0.6956  |    0.6878  | 0.5251 | [Download](https://drive.google.com/file/d/1Q6OOn5hMB4cskH09o72B3MeBiD_9cgED/view?usp=sharing)|
|    Exp-12      |    SegFormer-B1   |   AdamW     |  Focal |      New       |       8      |    0.6842   |   0.6485  |    0.6632  | 0.4988 | [Download](https://drive.google.com/file/d/1ovCPeE5iI9vlNaT6lnoVX1EjgKjucfSO/view?usp=sharing)|
|    Exp-13      |    SegFormer-B2   |   AdamW     |  Focal |      New       |       8      |    0.6893   |   0.6960  |    0.6920  | 0.5297 | [Download](https://drive.google.com/file/d/1sDuFbgL--3NIKww84AwVDEt-Ylw0-SKw/view?usp=sharing)|
|    Exp-14      |    SegFormer-B2   |    Adam     |  Focal |      New       |       8      |    0.7061   |   0.6974  |    0.7017  | 0.5411 | [Download](https://drive.google.com/file/d/1nCRrwshORyxXxZtp0r2iZofEihj9SO_o/view?usp=sharing)|
|    Exp-15      |  Unet++ TIMM [2]  |    Adam     |  Dice  |      Old       |      16      |    0.5141   |   0.6970  |    0.5772  | 0.4199 | [Download](https://drive.google.com/file/d/1D1uozmGI-fPKwCAE-HwsY-u1oxcBBsuw/view?usp=sharing)|
