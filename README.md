# Diabetes Prediction App

This diabetes prediction app is designed to assess the likelihood of having diabetes based on various health parameters. Utilizing neural networks, the application provides predictions indicating whether the user is diabetic, not diabetic, or has a potential risk of diabetes.

## Features

- **Predictive Analysis:** The app employs neural networks to analyze input features such as gender, age, urea, creatinine (cr), HbA1c, cholesterol (chol), triglycerides (tg), high-density lipoprotein (hdl), low-density lipoprotein (ldl), very-low-density lipoprotein (vldl), and body mass index (BMI).

- **Prediction Categories:**
  - **Diabetic:** Indicates a positive prediction for diabetes.
  - **Non-Diabetic:** Indicates a negative prediction for diabetes.
  - **Potential Risk:** Suggests a possibility of diabetes, prompting further attention or medical consultation.

- **Flask Framework:** The app is developed using the Flask framework, ensuring a user-friendly and responsive web interface.

## Usage

1. **Input Data:** Provide the required health parameters as input.
2. **Prediction:** The app processes the input through neural networks.
3. **Result:** Receive the prediction result with the corresponding category.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/mansh7763/diabetes-prediction.git
   cd diabetes-prediction
