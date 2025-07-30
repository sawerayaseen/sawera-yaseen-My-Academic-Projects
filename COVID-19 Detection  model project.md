



## 🦠 COVID-19 Detection from Chest X-Ray Images using Deep Learning
📖 Overview
This project focuses on automated detection of COVID-19 infection using chest X-ray images and deep learning techniques. With the outbreak of the COVID-19 pandemic, rapid and accurate diagnosis became critical. While RT-PCR tests are standard, they are time-consuming. Radiographic imaging (X-ray) has emerged as a fast alternative for screening COVID-19 patients.

This project leverages Convolutional Neural Networks (CNNs) and Transfer Learning to classify chest X-ray images into:

COVID-19 Positive

Normal (Healthy)

Viral Pneumonia
## ✨ Key Features
📊 Multi-class classification (COVID-19, Normal, Pneumonia)

📁 Uses the covid-chestxray-dataset-master from public repositories

🧠 Deep learning models: CNN, VGG16, ResNet50

✅ Real-time prediction support

📈 Accuracy, precision, recall, and confusion matrix visualization

📸 Visualizes model predictions on X-ray images

⚙️ Easy to run on CPU or GPU

🧼 Includes preprocessing like image normalization and resizing
## 🗂️ Dataset
We used the covid-chestxray-dataset-master, which contains:

X-ray images from COVID-19 patients

Healthy individuals

Patients with viral pneumonia

Preprocessing Steps:

Image resizing (typically 224x224 or 299x299)

Data augmentation (rotation, zoom, flip)

Normalization (pixel value scaling)

Split into training, validation, and test sets


## Sample Folder Structure:
dataset/
  ├── train/
  │   ├── COVID/
  │   ├── NORMAL/
  │   └── PNEUMONIA/
  ├── test/
  │   ├── COVID/
  │   ├── NORMAL/
  │   └── PNEUMONIA/

## 🧠 Models Used
✅ Baseline CNN
3 Convolutional Layers

ReLU + MaxPooling

Fully connected Dense Layers

Softmax activation

✅ Transfer Learning Models
VGG16

Pretrained on ImageNet

Fine-tuned last few layers

ResNet50

Deeper architecture

Skip connections prevent vanishing gradient


## Training Details:
Loss: Categorical Crossentropy

Optimizer: Adam / RMSProp

Epochs: 20-30

Batch Size: 32
## 📊 Results
Evaluation Metrics:
Model	Accuracy	Precision	Recall	F1-Score
CNN	87.6%	85.1%	86.7%	85.9%
VGG16	94.2%	93.8%	94.0%	93.9%
ResNet50	96.1%	95.5%	96.3%	95.9%

Confusion matrix and ROC curves included

ResNet50 showed the best generalization


## 🔮 Future Work
✅ Add support for CT scan images

🌐 Build a Flask or Streamlit web app

💬 Add model explanation (e.g., Grad-CAM visualization)

🌍 Multilingual support for global deployment

🧪 Semi-supervised learning for unlabeled data


## 📄 License
https://drive.google.com/drive/folders/1FVoVy8b8Pnn1gtAlaA75bSlnktSOtX4x?usp=sharing