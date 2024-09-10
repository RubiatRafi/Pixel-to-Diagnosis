# Lung and Colon Cancer Classification using EfficientNetB3 and Explainable AI

This repository implements a deep learning model based on **EfficientNetB3** for classifying lung and colon cancer from histopathological images. The model is enhanced with **Explainable AI** (XAI) techniques such as **LIME** and **SHAP** to provide interpretable insights into its decision-making process, ensuring transparency and improving clinical trust.

## Features
- **Model Architecture**: A modified **EfficientNetB3** architecture, fine-tuned for superior performance in medical image classification tasks.
- **Explainability**: Incorporates **LIME** (Local Interpretable Model-agnostic Explanations) and **SHAP** (SHapley Additive exPlanations) to highlight important features in the images, making the model's predictions more understandable.
- **Dataset**: Trained on a dataset of 25,000 histopathological images across five classes, including benign and cancerous lung and colon tissues.
- **Performance**: Achieves an outstanding accuracy of 99.66%, with high precision (99.78%), recall (98.58%), and F1-score (99.18%).

## Technologies Used
- **EfficientNetB3**: A scalable deep learning model with excellent accuracy and computational efficiency.
- **Explainable AI**: LIME and SHAP for model interpretability.
- **Python Libraries**: TensorFlow, Keras, NumPy, Matplotlib for model development and evaluation.

## How to Run
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/cancer-classification.git
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Download the dataset and place it in the `data/` folder.

4. Train the model:
    ```bash
    python train_model.py
    ```

5. Visualize the model's predictions with LIME and SHAP:
    ```bash
    python explain_model.py
    ```

## Conclusion
This project demonstrates the effectiveness of **EfficientNetB3** for lung and colon cancer classification and emphasizes the importance of explainability in AI-driven medical diagnostics.
