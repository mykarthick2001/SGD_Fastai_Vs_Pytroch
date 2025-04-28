# SGD_Fastai_Vs_Pytroch

#🧠 Fastai vs PyTorch: MNIST Digit Classification

This project explores a side-by-side comparison between Fastai and vanilla PyTorch using the MNIST handwritten digits dataset.

##🔍 Objective
To compare:
-🚀 Training loop design
-🎯 Accuracy
-🔧 Code complexity
-📊 Model performance (Confusion Matrix)

Using the same dataset and a similar Simple Neural Network (SimpleNN) architecture.
---
##📁 Dataset
MNIST Sample — Handwritten digits '3' and '7' subset:
-50% class '3'
-50% class '7'

Grayscale 28x28 pixel images

Learn more about MNIST

##🧪 Approaches Compared
###✅ Fastai
-Custom DataBlock pipeline with PILImageBW (grayscale)
-Learner API: Learner, fit_one_cycle()
-Built-in metrics, recorder, and interpretation tools

###🧱 PyTorch From Scratch
-Manual DataLoader, model, loss, optimizer
-Custom training loop with backpropagation
-Manual loss and accuracy tracking
-Confusion matrix plotted using sklearn

## 📈 Results Snapshot (After 5 Epochs)

|Framework	| Accuracy	| Code Length	| Visualizations|
|-----------|-----------|-------------|---------------|
|Fastai     |	~95%      |	~15 lines   |	✅ Built-in   |
|PyTorch    |	~93%      | ~75 lines   |	✅ Manual     |


###🧠 Key Learnings
-Fastai simplifies deep learning prototyping dramatically without losing flexibility.
-Manual PyTorch offers full control but requires more code and maintenance.
-Custom DataBlocks in Fastai allow efficient preprocessing pipelines.
-Visualization is critical for model evaluation.

###🛠️ Environment
-Python 3.11+
-fastai
-torch
-torchvision
-scikit-learn
-matplotlib


#How to Run
## Clone this repository
git clone https://github.com/yourusername/SGD_Fastai_Vs_PyTorch.git
cd SGD_Fastai_Vs_PyTorch

## Install required libraries
pip install -r requirements.txt

## Launch Jupyter Notebook
jupyter notebook
