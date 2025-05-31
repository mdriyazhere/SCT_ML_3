

# 🐶🐱 Dogs vs. Cats Image Classification with SVM

This repository contains a project focused on classifying images of dogs and cats using a **Support Vector Machine (SVM)** classifier. The implementation is done in Python using a Jupyter Notebook.

## 📁 Project Structure

- `Dog_vs_Cat_Classification.ipynb` – Jupyter Notebook containing data preprocessing, feature extraction, training, and evaluation using an SVM classifier.
- `README.md` – Project documentation.

## 🧠 Model Overview

We use a Support Vector Machine (SVM) to distinguish between dog and cat images. Instead of deep learning (CNNs), this model uses traditional machine learning with feature extraction techniques (such as resizing, grayscale, flattening, or HOG) to classify images.

## 📊 Dataset

**Dataset:** [Kaggle Dogs vs. Cats Dataset](https://www.kaggle.com/c/dogs-vs-cats/data)

- You'll need to download the dataset manually from Kaggle due to license restrictions.
- After downloading, place the extracted `train` folder in the same directory as the notebook.

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Platinumgai/dogs-vs-cats-svm.git
cd dogs-vs-cats-svm
2. Install Dependencies
Make sure you have Python 3.x and pip installed. Then run:


pip install -r requirements.txt
If requirements.txt is not available, the following are the major libraries used:


pip install numpy matplotlib scikit-learn opencv-python
3. Run the Notebook
Launch Jupyter Notebook and open:


jupyter notebook Dog_vs_Cat_Classification.ipynb
Follow the steps in the notebook to preprocess the data, train the model, and evaluate its performance.

📈 Evaluation
The model's performance is evaluated using accuracy, precision, recall, and confusion matrix. You can also visualize the predictions on sample images.

🔍 Future Improvements
Incorporate HOG or SIFT for better feature extraction

Experiment with hyperparameter tuning of SVM

Add deep learning baseline for comparison

🧑‍💻 Author
Platinumgai – GitHub Profile
