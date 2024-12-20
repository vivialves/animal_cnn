# 🐾 Animal Classification with PyTorch
Welcome to the Animal Classification with PyTorch repository! 🦁🐶🐘 This project is designed to classify animals into 10 distinct categories using PyTorch deep learning models. Whether you're here to explore neural networks, benchmark performance, or simply admire the versatility of AI in image recognition, you're in the right place!

## 📚 **Dataset Overview**
The dataset used for this project is a well-known subset of animal classification images sourced from Google Image Search. Here's a quick overview:

Total Images: ~28,000
Number of Categories: 10

🐶 Dog

🐱 Cat

🐴 Horse

🕷️ Spider

🦋 Butterfly

🐔 Chicken

🐑 Sheep

🐄 Cow

🐿️ Squirrel

🐘 Elephant

Image Count per Category: Varies between 1.4K to 5K images.

Directory Structure: Each category has its own folder in the dataset's main directory.

## 🧠 **Model Architectures**
This repository includes training and evaluation of multiple neural network architectures for animal classification, such as:

AlexNet

ShuffleNet

EfficientNet

More architectures to come!

Each model has been evaluated based on accuracy, loss, and other key metrics, with visualized results for better insights.

## 📊 **Results**
We track training and validation performance for each model over multiple epochs. Metrics include:

- Accuracy
- Loss
- Precision, Recall, F1 Score
- Confusion Matrix
- Graphs of loss and accuracy are available in notebooks

### Training Metrics:
| Model           | Accuracy (Train) | Accuracy (Validation)  | Transfer Learning  |
|-----------------|------------------|------------------------|--------------------|
| AlexNet         | 57.71%           | 55.10%                 |                    |
| AlexNet-tf      | 52.87%           | 50.02%                 |     ✅            |
| ShuffleNet      | 77.84%           | 74.80%                 |                    |
| ShuffleNet-tf   | 88.49%           | 84.35%                 |     ✅            |
| EfficientNet    | 73.11%           | 73.35%                 |                    |
| EfficientNet-tf | 89.18%           | 86.94%                 |     ✅             |


## 🚀 **How to Get Started**
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/animal-classification.git
cd animal-classification
```
### 2️⃣ Install Dependencies
Create a virtual environment and install the required Python packages:
```bash
pip install -r requirements.txt
```
### 3️⃣ Download the Dataset
The dataset is not included in this repository. You can download it from Dataset Link: https://www.kaggle.com/datasets/rajatdulal/animal10.

Ensure the dataset is organized as described in the dataset structure section.

### 4️⃣ Data Analysis
Run the training script for your chosen model:
```bash
notebook data_analysis.ipynb
```
### 5️⃣ Train the Model
Run the training script for your chosen model:
```bash
notebook alexnet.ipynb
notebook alexnet-tf.ipynb --> Transfer learning
```
```bash
notebook shufflenet.ipynb
notebook shufflenet-tf.ipynb --> Transfer learning
```
```bash
notebook efficientnet.ipynb
notebook efficientnet-tf.ipynb --> Transfer learning
```

## 📁 **Directory Structure**
```
animal-classification/
├── data/
│   ├── dog/
│   ├── cat/
│   ├── horse/
│   ├── ...
├── models/
│   ├── alexnet.ipynb
│   ├── alexnet-tf.ipynb
│   ├── shufflenet.py
│   ├── shufflenet-tf.py
│   ├── efficientnet.py
│   ├── efficientnet-tf.py
├── results/
│   ├── alexnet_loss.png
│   ├── shufflenet_accuracy.png
├── requirements.txt
└── README.md
```

## 🛠️ **Features**
- Preprocessing: Image augmentation techniques such as rotation, flipping, and scaling.
- Custom Training Loop: PyTorch-based implementation of forward pass, backpropagation, and optimization.
- Metrics Tracking: Training and validation loss/accuracy graphs, confusion matrix, and classification reports.
- Multi-Model Support: Easily switch between different architectures for experimentation.

---

## 🔧 **Technologies Used**
- **Python**: PyTorch, TorchMetrics
- **Visualization**: Matplotlib, Seaborn, ScikitLearn, 

---

## 🔍 **Future Work**
- Add additional architectures (e.g., ResNet, DenseNet).
- Fine-tune hyperparameters for improved accuracy.
- Deploy the model with a web interface using Streamlit or Flask.
- Experiment with transfer learning for faster convergence.

---

## 🤝 **Contributing**
Contributions are welcome! If you have ideas for improvement or want to fix a bug, feel free to submit a pull request or open an issue.

---

## 📜 **License**
This project is licensed under the [GPL License](LICENSE).

---

## 📧 **Contact**
For questions or collaborations, feel free to reach out:
- **Author**: Viviane
- **LinkedIn**: https://www.linkedin.com/in/vivialves-developer/

---

Thank you for checking out this project! 🌟