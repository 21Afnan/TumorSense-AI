<p align="center">
  <img
    src="https://capsule-render.vercel.app/api?type=waving&height=200&section=header&text=TumoreSense%20AI&fontSize=45&fontColor=ffffff&animation=fadeIn&fontAlignY=38&color=16afe6&v=12"
    width="100%"
    alt="TumoreSense AI"
  />
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&height=2&color=16afe6" width="100%" alt="blue line"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/PyTorch-Deep%20Learning-EE4C2C?logo=pytorch&logoColor=white" alt="PyTorch"/>
  <img src="https://img.shields.io/badge/Python-Backend-yellow?logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/CNN-CustomModel-16afe6" alt="CNN"/>
  <img src="https://img.shields.io/badge/ResNet18-TransferLearning-0A2472" alt="ResNet18"/>
  <img src="https://img.shields.io/badge/MRI%20Dataset-4Classes-FF5733" alt="Dataset"/>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&height=2&color=16afe6" width="100%" alt="blue line"/>
</p>

## 🧠 Project Overview

**TumoreSense AI** is a **deep learning system for multi-class brain tumor classification** using MRI images.  
It identifies four categories: **Glioma, Meningioma, Pituitary Tumor, and No Tumor**.

📄 **Reference Paper:** [PDF Link](https://link.springer.com/article/10.1007/s10278-025-01686-1)  
🎥 **Demo Video:** [Insert Video Link]  
🌐 **Web Demo:** [Insert Website Link]

🚀 Developed by:

- **Afnan Shoukat** – Lead Model & Integration  
- **Usama Shahid** – Backend & Deployment  
- **Dure Addan Noor** – Data & Visualization  

---

## ✨ Key Features

### 🧩 1. Multi-Class Tumor Detection
- Detects Glioma, Meningioma, Pituitary, or No Tumor in MRI scans  
- Supports batch & single image prediction

### 🧠 2. Models Implemented
- **Custom CNN** – Lightweight, fast inference  
- **ResNet18** – Transfer Learning for higher accuracy

### ⚙️ 3. Evaluation & Visualization
- Training & validation curves  
- Confusion matrix & classification report  
- Sample predictions visualization  

### 📊 4. Dataset & Preprocessing
- MRI images with augmentation: rotation, flips, resizing, grayscale  
- Train/Validation/Test split  

### 💾 5. Model Management
- Save & load `.pth` trained weights  
- Flexible for further fine-tuning or deployment  

---

## 🗂️ Project Structure

```
tumore-sense-AI/
│
├── README.md                   # Project overview and instructions
├── requirements.txt            # Python dependencies
├── data/                       # Dataset instructions and folder structure (Kaggle link)
├── src/
│   ├── resnet_model.py         # ResNet18 implementation
│   └── simple_cnn.py           # Custom CNN implementation
├── results/
│   ├── resnet/                 # Accuracy, loss plots, confusion matrix for ResNet
│   └── cnn/                    # Accuracy, loss plots, confusion matrix for CNN
├── models/
│   ├── resnet/                 # Saved ResNet weights
│   └── cnn/                    # Saved CNN weights
├── paper/
│   └── reference_paper.pdf     # Paper PDF
└── screenshots/                # Sample prediction images
```

## 🏗️ Architecture Overview

```
flowchart TD
    A["MRI Input Images"] --> B["Data Preprocessing"]
    B --> C["Model Layer"]
    C --> D1["ResNet18"]
    D1 --> E["Prediction Output"]
    E --> F["Evaluation Metrics & Visualization"]
```

## 📥 Dataset

**Brain Tumor MRI Dataset** – 4 classes: Glioma, Meningioma, Pituitary Tumors, and No Tumor.

**Kaggle Link:** [Brain Tumor MRI Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset)

### 🔧 Download via Python (using `kaggle` API)

```python
# Install Kaggle API (if not already installed)
!pip install kaggle

# Make sure your Kaggle API token (kaggle.json) is in ~/.kaggle/

# Download the dataset
!kaggle datasets download -d masoudnickparvar/brain-tumor-mri-dataset
```

## 🚀 Installation & Setup

### 🔧 Prerequisites
- Python 3.10+
- PyTorch & torchvision
- Matplotlib, seaborn, scikit-learn, PIL (Pillow)

---

### ⚙️ Installation
```bash
# Clone the repository
git clone https://github.com/yourusername/tumore-sense-ai.git
cd tumore-sense-ai

# Install dependencies
pip install -r requirements.txt




## 💻 Running Models

### Custom CNN
```bash
python src/simple_cnn.py
python src/resnet_model.py

```



## 📊 Results

- **Accuracy & Loss Curves:** `results/resnet/` & `results/cnn/`  
- **Confusion Matrix & Classification Report:** saved in results folders  
- **Sample Predictions:** `screenshots/`  

| Model       | Test Accuracy |
|------------|---------------|
| Custom CNN | 92–94%        |
| ResNet18   | 96–97%        |

## 🖼️ Screenshots

- Sample Prediction  
- Accuracy & Loss Curves  

## 🔮 Future Enhancements

- Real-time MRI scanner integration with bounding boxes  
- Explainable AI (XAI) for model transparency  
- Web-based GUI for predictions  

## 🤝 Collaborators

| Name               | GitHub                                                 | LinkedIn                                                                |
|--------------------|--------------------------------------------------------|-------------------------------------------------------------------------|
| Afnan Shoukat      | [21Afnan] (https://github.com/21Afnan)                 | [Afnan Shoukat](https://linkedin.com/in/afnanshoukat)                   |            
| Hina Tanveer       | [Hina Tanveer](https://github.com/hinatanveer)         | [Hina Tanveer](https://linkedin.com/in/hinatanveer)                     |
| Usama Shahid       | [Usama Shahid](https://github.com/fewgets)             | [Usama Shahid  ](https://linkedin.com/in/-usamashahid)                  |
| Dur-e-Adan Noor    | [Dur-e-Adan Noor](https://github.com/dureadannoor-123) | [Dur-e-Adan Noor](https://www.linkedin.com/in/dure-adan-noor-29b01b2b5) |
| Salman Khan        | [Salman Khan](https://github.com/salmankhan)           |  [Salman Khan](https://linkedin.com/in/salmankhan)                      |


## 📬 Contact

- **Email:** afnanshoukat011@gmail.com  
- **GitHub:** [21Afnan](https://github.com/21Afnan)  
- **LinkedIn:** [Linkedin](www.linkedin.com/in/afnanshoukat)
