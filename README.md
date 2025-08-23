<h2>📱Mobile Phone Price Prediction</h2>

This repository contains a Jupyter Notebook that predicts mobile phone prices using machine learning models based on four key features:

  ⭐ Ratings

  🧠 RAM

  💾 ROM

  🔋 Battery Power



Two models are implemented and compared:

- Linear Regression
- Neural Network (Keras)

The Neural Network model outperforms the Linear Regressor in terms of prediction accuracy, as measured by RMSE and R² score.


<h2>📁 Files</h2>

- phone_price_prediction.ipynb: The main notebook containing data preprocessing, model training, evaluation, and prediction steps.

- checkpoints/: Directory where trained neural network models are saved during training (via Keras callbacks).



<h2>🧪 Models Used</h2>

🔹**Linear Regression**

  -   Implemented using scikit-learn
  -   Serves as a baseline for model comparison

🔹 **Neural Network**

  - Built using Keras with TensorFlow backend
  - Architecture:
      Dense layers with ReLU activation
      Dropout for regularization
  - Trained using mean_squared_error loss and Adam optimizer



📊 **Evaluation Metrics**

  Both models are evaluated using:
  - R² Score
  - Mean Squared Error (MSE)


  <h1>How to Run</h1>

1. Clone the repository:

          git clone https://github.com/your-username/mobile-price-prediction.git
          cd mobile-price-prediction


2. Install dependencies:

          pip install -r requirements.txt


3. Launch the Jupyter Notebook:

          jupyter notebook


Open phone_price_prediction.ipynb and run the cells.
