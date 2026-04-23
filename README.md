# Plant Disease Detection using Deep Learning

This project focuses on detecting plant diseases from leaf images using deep learning techniques. The goal is to build a model that can help identify plant health issues early, which can be useful for agriculture and crop monitoring.

---

## Dataset

The dataset used in this project is from Kaggle:
PlantVillage Dataset
https://www.kaggle.com/datasets/abdallahalidev/plantvillage-dataset

It contains labeled images of healthy and diseased plant leaves across multiple classes.

---

## Approach

The workflow followed in this project:

* Loaded and explored the dataset
* Performed image preprocessing (resizing, normalization)
* Split data into training and validation sets
* Built a deep learning model for classification
* Trained the model and monitored performance
* Evaluated accuracy and loss

The model learns patterns in leaf images to classify whether a plant is healthy or affected by a specific disease.

---

## Model Details

* Framework: TensorFlow / Keras
* Type: Convolutional Neural Network (CNN)
* Input: Leaf images
* Output: Disease class prediction

The model uses convolutional layers to extract features like texture, color variations, and patterns in leaves.

---

## Results

* Achieved good classification accuracy of 88.28% on validation data
* Model is able to distinguish between multiple plant diseases and healthy leaves

---

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/sahul-git/Plant-disease-Detection.git
   cd Plant-disease-Detection
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:

   * Open the `.ipynb` file in Jupyter Notebook or Google Colab
   * Execute all cells step by step

---

## Tech Stack

* Python
* TensorFlow / Keras
* NumPy, Pandas
* Matplotlib / Seaborn

---

## Notes

This project was built as part of learning deep learning and image classification.
Future improvements can include:

* Better model tuning
* Deployment as a web app
* Real-time disease detection

---

## 👨‍💻 Author

Sahul Kumar
GitHub: https://github.com/sahul-git
