# Automatic Road Extraction from Historical Maps Using Transformer-Based SegFormers
This repository contains the code for the paper [Automatic Road Extraction from Historical Maps Using Transformer-Based SegFormers](https://www.mdpi.com/2220-9964/13/12/464)

Aim
---------------------

In this research, we developed a novel approach to automatically extract five different road types from historical maps using transformer-based SegFormer models. We utilized a digitized dataset derived from Deutsche Heereskarte 1:200,000 Türkei maps to evaluate the effects of various encoders, batch sizes, loss functions, and augmentation techniques. The goal was to enhance the accuracy and efficiency of road segmentation from historical maps, surpassing the limitations of traditional CNN-based methods.

Sample Outputs
---------------------
![sample_figure](https://github.com/user-attachments/assets/224ad592-bb67-47c7-97c8-ff6a915804b0)


Experiment Results and Weights
---------------------

| Experiment No  |       Model       | Optimizer   |  Loss  | Augmentation   |  Batch Size  |  Precision  |   Recall  |  F1 Score  |   IoU  |  Weights  |  Notebook |
|:--------------:|:-----------------:|:-----------:|:------:|:--------------:|:------------:|:-----------:|:---------:|:----------:|:------:|:---------:|:---------:|
|     Exp-1      |    SegFormer-B0   |    Adam     |  Dice  |      Old       |      16      |    0.6031   |   0.7043  |    0.6490  | 0.4807 | [Download](https://drive.google.com/file/d/1kGyaS1mYwsMZoop0rLMZrYLVZhOQbf53/view?usp=sharing)| [Notebook](experiments/exp-1.ipynb)
|     Exp-2      |    SegFormer-B0   |    Adam     |  Focal |      Old       |      16      |    0.6876   |   0.5579  |    0.6158  | 0.4455 | [Download](https://drive.google.com/file/d/1hGvj3WeG86YW45F__9b9_9dfijBHkkS7/view?usp=sharing)| [Notebook](experiments/exp-2.ipynb)
|     Exp-3      |    SegFormer-B0   |   AdamW     |  Focal |      Old       |      16      |    0.6605   |   0.5932  |    0.6242  | 0.4547 | [Download](https://drive.google.com/file/d/1YAKRhm2yk9MJ4dzGJQuyaxMMbkM17Mzw/view?usp=sharing)| [Notebook](experiments/exp-3.ipynb)
|     Exp-4      |    SegFormer-B0   |   AdamW     |  Focal |      No        |      16      |    0.6751   |   0.6780  |    0.6756  | 0.5110 | [Download](https://drive.google.com/file/d/1wom2dvOfiqdTH6CCnP94CiGq87ZmfacY/view?usp=sharing)| [Notebook](experiments/exp-4.ipynb)
|     Exp-5      |    SegFormer-B0   |    Adam     |  Dice  |      New       |      16      |    0.6293   |   0.7203  |    0.6697  | 0.5053 | [Download](https://drive.google.com/file/d/1l1wKY53ZPs0zwGYWhyRWy9Nkrt-vzWOF/view?usp=sharing)| [Notebook](experiments/exp-5.ipynb)
|     Exp-6      |    SegFormer-B0   |   AdamW     |  Focal |      New       |      16      |    0.7057   |   0.6675  |    0.6853  | 0.5216 | [Download](https://drive.google.com/file/d/1mviJYHOvYNcN5DjLgptrXz_zKVVBgdKU/view?usp=sharing)| [Notebook](experiments/exp-6.ipynb)
|     Exp-7      |    SegFormer-B0   |   AdamW     |  Dice  |      New       |      16      |    0.6668   |   0.6901  |    0.6780  | 0.5136 | [Download](https://drive.google.com/file/d/17580lyBjPzWm5xl_ai9A3zqZ-kixyA2a/view?usp=sharing)| [Notebook](experiments/exp-7.ipynb)
|     Exp-8      |    SegFormer-B0   |    Adam     |  Focal |      New       |      16      |    0.6966   |   0.6831  |    0.6889  | 0.5259 | [Download](https://drive.google.com/file/d/1fPcXRnwVP74-6RX0L7m9AOlruJHHQZ4N/view?usp=sharing)| [Notebook](experiments/exp-8.ipynb)
|     Exp-9      |    SegFormer-B0   |   AdamW     |  Focal |      New       |       8      |    0.7015   |   0.6434  |    0.6717  | 0.5067 | [Download](https://drive.google.com/file/d/1c4laoVCApKi2jjNMkBzQvQT-z5xgaDjr/view?usp=sharing)| [Notebook](experiments/exp-9.ipynb)
|    Exp-10      |    SegFormer-B1   |   AdamW     |  Focal |      New       |      16      |    0.6928   |   0.6886  |    0.6905  | 0.5279 | [Download](https://drive.google.com/file/d/1MuKlt5RXcX-x7fq9JNeVfH3UZm7BiZOu/view?usp=sharing)| [Notebook](experiments/exp-10.ipynb)
|    Exp-11      |    SegFormer-B1   |    Adam     |  Focal |      New       |      16      |    0.6822   |   0.6956  |    0.6878  | 0.5251 | [Download](https://drive.google.com/file/d/1Q6OOn5hMB4cskH09o72B3MeBiD_9cgED/view?usp=sharing)| [Notebook](experiments/exp-11.ipynb)
|    Exp-12      |    SegFormer-B1   |   AdamW     |  Focal |      New       |       8      |    0.6842   |   0.6485  |    0.6632  | 0.4988 | [Download](https://drive.google.com/file/d/1ovCPeE5iI9vlNaT6lnoVX1EjgKjucfSO/view?usp=sharing)| [Notebook](experiments/exp-12.ipynb)
|    Exp-13      |    SegFormer-B2   |   AdamW     |  Focal |      New       |       8      |    0.6893   |   0.6960  |    0.6920  | 0.5297 | [Download](https://drive.google.com/file/d/1sDuFbgL--3NIKww84AwVDEt-Ylw0-SKw/view?usp=sharing)| [Notebook](experiments/exp-13.ipynb)
|    Exp-14      |    SegFormer-B2   |    Adam     |  Focal |      New       |       8      |    0.7061   |   0.6974  |    0.7017  | 0.5411 | [Download](https://drive.google.com/file/d/1nCRrwshORyxXxZtp0r2iZofEihj9SO_o/view?usp=sharing)| [Notebook](experiments/exp-14.ipynb)
|    Exp-15      |  Unet++ TIMM [[2]](https://ieeexplore.ieee.org/document/9882054)  |    Adam     |  Dice  |      Old       |      16      |    0.5141   |   0.6970  |    0.5772  | 0.4199 | [Download](https://drive.google.com/file/d/1D1uozmGI-fPKwCAE-HwsY-u1oxcBBsuw/view?usp=sharing)| [Reference](https://ieeexplore.ieee.org/document/9882054)

Dataset
---------------------
The dataset used in this study are openly available at [here](https://urbanoccupations.ku.edu.tr/historical-road-types-for-turkey-1940s).

System-specific notes
---------------------
The code was implemented in Python(3.10.12) and PyTorch(2.1.2) on Windows OS. The implementation uses the [segmentation-models-pytorch](https://github.com/qubvel-org/segmentation_models.pytorch), [transformers](https://github.com/huggingface/transformers), and [datasets](https://github.com/huggingface/datasets) libraries for developing and evaluating the models.


Citation
---------------------
Please kindly cite our paper if this code and the dataset used in the study is useful for your research.

Sertel, E.; Hucko, C.M.; Kabadayı, M.E. Automatic Road Extraction from Historical Maps Using Transformer-Based SegFormers. ISPRS Int. J. Geo-Inf. 2024, 13, 464. https://doi.org/10.3390/ijgi13120464
