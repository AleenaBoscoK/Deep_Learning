# Deep Learning in PyTorch

Coursework notebooks from my Deep Learning course in the B.Tech CSE (AI & ML) program at Vellore Institute of Technology, covering core architectures in PyTorch, from a basic feed-forward network to GANs and object detection. They include models built from scratch, transfer learning with pretrained networks, and fine-tuning for object detection.

## Notebooks

| Topic | Notebook | What it does | Data |
|---|---|---|---|
| **Neural network basics** | [`ann-model.ipynb`](ann-model.ipynb) | Feed-forward neural network with two hidden layers for classification | Sample CSV dataset |
| **CNNs from scratch** | [`alexnet-fromscratch.ipynb`](alexnet-fromscratch.ipynb) | AlexNet-style CNN built from scratch | MNIST |
| | [`rock-paper-scissors-dl.ipynb`](rock-paper-scissors-dl.ipynb) | Three-layer CNN that classifies rock, paper and scissors hand gestures | Rock-Paper-Scissors images |
| **Transfer learning** | [`vgg-dl.ipynb`](vgg-dl.ipynb) | Pretrained VGG-19 (ImageNet) with a new classifier head | CIFAR-10 |
| | [`resnet.ipynb`](resnet.ipynb) | Pretrained ResNet-50 with a new classifier head | CIFAR-10 |
| **Sequence models** | [`lstm-dl.ipynb`](lstm-dl.ipynb) | LSTM for time-series forecasting of stock prices | Apple (AAPL) prices, 2010–2020 |
| **Generative models** | [`Autoencoder.ipynb`](Autoencoder.ipynb) | Fully connected autoencoder that compresses and reconstructs images | MNIST |
| | [`dcgan_mnist.ipynb`](dcgan_mnist.ipynb) | DCGAN that generates handwritten digits | MNIST |
| **Object detection** | [`fastercnn.ipynb`](fastercnn.ipynb) | Object detection on a test image with pretrained Faster R-CNN (ResNet-50 FPN) and YOLOv8 | Test image (COCO classes) |
| | [`fine-tuning-fasterrcnn.ipynb`](fine-tuning-fasterrcnn.ipynb) | Fine-tunes Faster R-CNN to detect fruit | Fruit Images for Object Detection (Kaggle) |

## Built with

Python · PyTorch · torchvision · scikit-learn · pandas · Matplotlib · Jupyter (Kaggle and Google Colab)

## Run a notebook

Open any notebook in [Google Colab](https://colab.research.google.com/) or Kaggle, or locally with Jupyter after installing `torch`, `torchvision`, `pandas`, `scikit-learn` and `matplotlib`. The LSTM notebook also needs `yfinance`; the object detection notebooks use `ultralytics` and a Kaggle API token to download the dataset.
