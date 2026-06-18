# Deep Learning Projects

A collection of deep learning assignments implemented from scratch using **PyTorch**.  
All notebooks are fully executed with outputs, plots, and results included.

---

## Projects

###  MLP Experiments
Exploring how architecture choices affect learning on both synthetic and real datasets.

- 5 MLP architectures compared (depth & width study)
- Activation functions: ReLU, Tanh, Sigmoid, LeakyReLU
- Regularization: Dropout vs. L2
- Hyperparameter sweep: learning rate, batch size, SGD vs. Adam
- Real-world dataset: **CovType** (multiclass classification)

---

###  CNN on CIFAR-10
Image classification with convolutional networks and transfer learning.

- Two CNN architectures: lightweight baseline vs. regularized (BatchNorm + Dropout + L2)
- 6-config hyperparameter grid search evaluated by Macro F1
- Data augmentation applied correctly (train-only) with leakage demo
- Transfer learning: **ResNet-18** fine-tuned on CIFAR-10 (two-phase: frozen → full)

---

###  RNN Text Classification
News article classification using recurrent networks.

- Custom NLP pipeline: tokenization, vocabulary, padding, DataLoader
- GRU-based classifier with stacked layers and dropout
- Hyperparameter search: hidden size, sequence length
- Comparison: **GRU vs. BiGRU**
- Dataset: **AG News** (4-class classification)

---

## Stack

`Python` · `PyTorch` · `torchvision` · `scikit-learn` · `NumPy` · `Pandas` · `Matplotlib`
