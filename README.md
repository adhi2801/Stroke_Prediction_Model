# Stroke Prediction Model  

This project uses deep learning to predict the risk of stroke based on medical data. It includes feature preprocessing, model training using TensorFlow/Keras, and explainability techniques such as SHAP and LIME to interpret the model’s predictions.  

## Project Overview  

- Uses a neural network to classify whether a patient is at risk of stroke.  
- Implements data preprocessing, including handling missing values and encoding categorical features.  
- Evaluates model performance using accuracy, loss, and validation metrics.  
- Explains predictions with SHAP (SHapley Additive Explanations) and LIME (Local Interpretable Model-agnostic Explanations).  

## Project Structure  

Stroke_Prediction_Model
├── Stroke_Prediction_Model.ipynb # Jupyter Notebook with full implementation
├── healthcare-dataset-stroke-data.csv # Dataset used for training and evaluation
├── README.md # Project documentation
├── requirements.txt # List of dependencies



## Setup Instructions  

### Clone the Repository  

git clone https://github.com/your-username/Stroke_Prediction_Model.git cd Stroke_Prediction_Model

### Install Dependencies  

pip install -r requirements.txt

### Run the Jupyter Notebook  

jupyter notebook
- Open `Stroke_Prediction_Model.ipynb` and run the cells step by step.

## Model Performance  

| Epoch | Training Accuracy | Validation Accuracy | Loss |  
|--------|------------------|--------------------|------|  
| 1      | 94.21%           | 94.97%             | 0.2204 |  
| 10     | 95.13%           | 95.34%             | 0.1395 |  
| 20     | 95.37%           | 94.95%             | 0.1274 |  
| 50     | 96.56%           | 92.92%             | 0.0889 |  

## Explainability with SHAP and LIME  

This model includes SHAP and LIME to explain individual predictions:  
- SHAP: Shows the impact of each feature on model output.  
- LIME: Provides interpretable explanations for predictions.  

Example insights:  
- Higher age, heart disease, and glucose levels increase stroke risk.  
- BMI, smoking status, and residence type also influence predictions.  

## References  

- [SHAP for Model Explainability](https://shap.readthedocs.io/en/latest/)  
- [LIME for Model Interpretation](https://marcotcr.github.io/lime/)  
- [Stroke Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset)  

---

Replace **`your-username`** with your actual GitHub username before pushing the repository.  

Let me know if you need any modifications.  

