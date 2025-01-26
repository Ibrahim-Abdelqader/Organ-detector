# Organ detector

<img src="https://github.com/user-attachments/assets/7870dabe-12a9-4896-9712-3e97f96665d8" height="320" width="400"/>
<img src="https://github.com/user-attachments/assets/d80f31bf-30d4-4f79-8e91-e5cc4eece2dc" width="400" />
<img src="https://github.com/user-attachments/assets/8d6e6220-d7a7-46e5-a96a-1c6410f2da3c" height="400" width="400"/>
<img src="https://github.com/user-attachments/assets/e7582cb9-2d47-44d9-a288-04f9e50e33ca" height="400" width="400"/>

## 📚 Overview
This project implements a deep learning Convolutional Neural Network (CNN) to classify medical organ images into four categories: Heart, Brain, Liver, Limbs.

---

## 🗒️ Table of content
1. [📽️ Video](#-Video)
2. [📂 Project Structure](#-project-structure)
3. [🛠️ Prerequisites](#-prerequisites)
4. [✨ Key Features](#-key-features)
5. [🛠️ Installation](#-installation)
6. [📊 Dataset Preparation](#-dataset-preparation)
7. [🧠 Model Architecture](#-model-architecture)
8. [🚀 Training](#-training)
9. [🪄 Usage](#-usage)
    - [Training the Model](#training-the-model)
    - [Predicting with the Model](#predicting-with-the-model)
10. [📈 Performance Metrics](#-performance-metrics)
11. [💾 Model Saving](#-model-saving)
12. [🛠️ Customization](#-customization)
13. [⚠️ Limitations](#️-limitations)
14. [📈 Future Improvements](#-future-improvements)
15. [🤝 Contributions](#-contributions)
16. [📜 License](#-license)
17. [📧 Contact](#-contact)

---

## 📽️ Video
https://github.com/user-attachments/assets/9bad4944-375d-4681-96f8-1f644bd2db2d

---
## 📂 Project Structure
```
project_root/
│
├── data_sets/
│   ├── heart/
│   ├── brain/
│   ├── liver/
│   └── limbs/
│
├── test_data/
│   └── NONE/
│
├── save_model/
│   └── organsClssify.h5
│
└── logs/
```

## 🛠️ Prerequirments
- Python 3.8+
- TensorFlow
- Numpy
- Matplotlib

## ✨ Key Features
- Image classification using CNN
- Data augmentation
- TensorBoard logging
- Model saving and loading functionality
- Visulization of training metrics

## 🛠️ Installation
1. Clone the repository
2. Install required dependencies:
```bash
pip install tensorflow numpy matplotlib
```

## 📊 Dataset Preparation
- Organize images in `data_sets/` directory
- Each subdirectory represents a different organ class
- Recommended image size: 256x256 pixels

## 🧠 Model Architecture
- Convolutional layers for feature extraction
- MaxPooling for dimensionality reduction
- Dropout for preventing overfitting
- Dense layers for classification

## 🚀 Training
- Uses Adam optimizer
- Categorical cross-entropy loss
- 5 training epochs
- Automatic train/validation/test split

## 🪄 Usage
### Training the Model
```python
# Run the main script to train the model
python organ_classification.py
```

### Predicting with the Model
```python
test_model('path/to/test_image.jpg')
```

## 📈 Performance Metrics
- Training and validation loss tracked
- Training and validation accuracy visualized
- Final test set evaluation provided

## 💾 Model Saving
- Trained model saved as `organsClssify.h5`
- Can be loaded for future predictions

## 🛠️ Customization
- Adjust hyperparameters in the script
- Modify model architecture as needed

## ⚠️ Limitations
- Requires diverse and well-labeled training data
- Performance depends on image quality and dataset composition

## 📈 Future Improvements
- Increase training epochs
- Implement more advanced data augmentation
- Experiment with deeper network architectures
- 
---

## 🤝 Contributions
Contributions are welcome! Feel free to fork this repository, create a branch, and submit a pull request with your enhancements.

---

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 📧 Contact
If you have any questions or suggestions, feel free to reach out via GitHub or email at [Ibrahim.Ibrahim051@eng-st.cu.edu.eg]

