# Chronic-Kidney-Diease-Analysis-
Deep learning project for detecting Chronic Kidney Disease (Normal, Cyst, Stone, Tumor) from CT scan images with TensorFlow and Gradio.

# Chronic Kidney Disease CT Image Classification

This project uses a deep learning model (CNN) to classify kidney CT scan images into:
- Normal
- Cyst
- Stone
- Tumor
- Kaggle Dataset Link :- https://www.kaggle.com/datasets/nazmul0087/ct-kidney-dataset-normal-cyst-tumor-and-stone

The model is trained on a labeled dataset and deployed with **Gradio** for easy testing.

---

## 🚀 Features
- Train CNN model on CT kidney dataset
- Upload an image and get predictions in real-time
- Gradio web UI for interactive testing

---

## 📂 Project Structure
- `kidney_training.ipynb` → Jupyter/Colab notebook with model training + Gradio demo
- `kidney_model.keras` → Saved model 
- `requirements.txt` → Required dependencies

---

## ▶️ Run on Colab
1. Open the notebook in Google Colab.
2. Run all cells to train the model.
3. At the end, Gradio UI will launch inside Colab:
   - Upload an image → get prediction + confidence score.

---

## 🛠️ Tech Stack
- TensorFlow / Keras
- NumPy, Pandas, Matplotlib
- Gradio (for UI)
