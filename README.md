<p align="center">
  <img src="./assets/banner.svg" alt="Neural Network Classification" width="100%"/>
</p>

<p align="center">
  <a href="https://github.com/your-username/neural-network-classification">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=18&duration=2600&pause=900&color=C9CCD1&center=true&vCenter=true&width=720&height=40&lines=Feed+it+data.+Watch+it+learn.;Hidden+layers.+Chrome+finish.;Classifying+the+world+in+high+definition.;Y2K+energy.+Real+accuracy." alt="typing animation"/>
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/PYTHON-3.10+-C9CCD1?style=for-the-badge&logo=python&logoColor=black&labelColor=000000"/>
  <img src="https://img.shields.io/badge/TENSORFLOW-KERAS-C9CCD1?style=for-the-badge&logo=tensorflow&logoColor=black&labelColor=000000"/>
  <img src="https://img.shields.io/badge/NUMPY-READY-C9CCD1?style=for-the-badge&logo=numpy&logoColor=black&labelColor=000000"/>
  <img src="https://img.shields.io/badge/STATUS-TRAINING-FF6EC7?style=for-the-badge&labelColor=000000"/>
</p>

<img src="./assets/divider.svg" width="100%" alt=""/>

## ✦ ABOUT

A **neural network classification model** built from scratch to sort inputs into
classes. Data goes in, passes through stacked hidden layers, and comes out the
other side as a softmax probability for every class.

<p align="center">
  <img src="./assets/network.svg" alt="animated neural network" width="100%"/>
</p>

<img src="./assets/divider.svg" width="100%" alt=""/>

## ✦ FEATURES

| ✧ | MODULE | DESCRIPTION |
|---|--------|-------------|
| ⛓ | **Preprocessing** | Cleaning, scaling, encoding, train/val/test split |
| ⛓ | **Model** | Fully connected network, ReLU hidden layers, softmax output |
| ⛓ | **Training** | Adam optimizer, early stopping, loss and accuracy tracking |
| ⛓ | **Evaluation** | Accuracy, precision, recall, F1, confusion matrix |
| ⛓ | **Inference** | Load the saved model and predict on new data |

<img src="./assets/divider.svg" width="100%" alt=""/>

## ✦ QUICK START

```bash
# clone
git clone https://github.com/your-username/neural-network-classification.git
cd neural-network-classification

# install
pip install -r requirements.txt

# train
python train.py --epochs 100

# predict
python predict.py --input data/sample.csv
```

<p align="center">
  <img src="./assets/terminal.svg" alt="animated training terminal" width="85%"/>
</p>

<img src="./assets/divider.svg" width="100%" alt=""/>

## ✦ ARCHITECTURE

```
INPUT  ──►  DENSE(128, relu)  ──►  DENSE(64, relu)  ──►  DENSE(n_classes, softmax)
```

| Hyperparameter | Value |
|----------------|-------|
| Optimizer | Adam |
| Learning rate | 0.001 |
| Loss | Categorical cross-entropy |
| Batch size | 32 |
| Epochs | 100 |

## ✦ RESULTS

| Metric | Score |
|--------|-------|
| Accuracy | `--` |
| Precision | `--` |
| Recall | `--` |
| F1 | `--` |

## ✦ PROJECT STRUCTURE

```
├── data/            # datasets
├── models/          # saved models
├── notebooks/       # experiments
├── train.py
├── predict.py
├── requirements.txt
└── README.md
```

## ✦ ROADMAP

- [x] Baseline network
- [ ] Hyperparameter tuning
- [ ] Dropout and regularization
- [ ] Confusion matrix visuals
- [ ] Deploy as an API

<img src="./assets/divider.svg" width="100%" alt=""/>

<p align="center">
  <sub>✧ built with loss, gradients and a little chrome ✧</sub>
</p>