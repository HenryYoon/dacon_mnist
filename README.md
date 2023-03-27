This repository (repo) contains source code which is submitted to the Dacon competition: [월간 데이콘 컴퓨터 비전 학습 경진대회](https://dacon.io/competitions/official/235626/overview/description).

In this repo, I applied Knowledge Distillation for modelling MNIST data.

Model spec:

- Teacher model: [Wide ResNet-101-2](https://pytorch.org/vision/main/models/generated/torchvision.models.wide_resnet101_2.html)
- Student model: [ResNet-50](https://pytorch.org/vision/main/models/generated/torchvision.models.resnet50.html)

As a result, I attained rank 55 out of 396 (top 13%).

## Usage

First, you need to install required libraries with this command

```python
pip install -r requirements.txt
```

If you want to run our code, please input this command

```python
python ./src/main.py
```

## Tech Stack
* Data: Torchvision, Pandas, Pillow
* AI: PyTorch

## License

[Apache License](LICENSE) © Hee Seung Yun
