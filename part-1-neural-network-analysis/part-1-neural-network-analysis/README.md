# Neural Network Fundamentals and Training Behavior Analysis

## Project Overview

This project builds and analyses a feed-forward neural network to predict customer churn 
from a structured dataset. The focus is not just on model accuracy, but on understanding 
how neural networks learn — through forward pass, loss calculation, backpropagation, and 
parameter updates.

---

## 📂 Dataset

The dataset used in this project is sourced from the shared Google Drive folder:

[Click here to access the dataset](https://drive.google.com/drive/folders/1akV6po4Nrgkc3yQrJkzA6cJlV-wBvUYs?usp=sharing)


---

## Repository Structure

- `notebook.ipynb` — main project notebook with all tasks
- `results/` — output files from model training
  - `model_comparison_table.png` — hyperparameter experiment comparison table
  - `evaluation_outputs.png` — Experiment 4 confusion matrix
- `requirements.txt` — required Python libraries
- `README.md` — project documentation

---

## Tasks Implemented

**Task 1 — Dataset Understanding**
Basic exploration of the customer churn dataset including shape, feature types, target 
distribution, missing value check, and statistical summary.

**Task 2 — Data Preprocessing**
Handles missing values, encodes categorical features, scales numerical features using 
StandardScaler, and splits data into training and testing sets.

**Task 3 — Neural Network Model Building**
Builds a Sequential neural network with two hidden layers, ReLU activation, Sigmoid 
output layer, binary crossentropy loss, and Adam optimizer.

**Task 4 — Training and Evaluation**
Trains the model for 50 epochs and evaluates using training/testing accuracy, loss, 
confusion matrix, and classification report. Results highlight class imbalance as a 
key challenge.

**Task 5 — Hyperparameter Experimentation**
Runs four experiments modifying activation functions, batch size, class weights, epochs, 
dropout, and learning rate. Results summarised in a comparison table.

**Task 6 — Final Reflection**
Written analysis covering the role of weights and biases, activation functions, learning 
rate behaviour, and signs of underfitting and overfitting observed across experiments.

---

## 🛠 Technologies Used

- 🐍 Python
- 📓 Jupyter Notebook
- 🐼 Pandas — data manipulation and analysis
- 🔢 NumPy — numerical computations
- 📊 Matplotlib — plotting and visualisation
- 🎨 Seaborn — statistical visualisation
- 🤖 Scikit-learn — preprocessing and evaluation metrics
- 🧠 TensorFlow / Keras — neural network building and training

---

## ▶️ How to Run

1. Download the dataset from the link above and place it in the project folder
2. Open `notebook.ipynb` in Jupyter Notebook or VS Code
3. Run all cells in order
4. Output images will be saved to the `results/` folder

---

## 📝 Notes

- All notebooks are well-commented for clarity
- Dataset files are not included in this repository.
