## NeuralRetention Engine


📌 Description

    This project is a Deep Learning-based Classification system designed to predict customer churn for banking institutions. By leveraging Artificial Neural Networks (ANN), the system analyzes customer demographics and financial behavior to identify those at high risk of leaving the bank, enabling proactive retention strategies.



🚀 Features

    - Deep Learning Integration: Utilizes a multi-layer ANN trained with TensorFlow/Keras for high-accuracy classification.

    - Robust Preprocessing Pipeline: Includes automated Label Encoding, One-Hot Encoding, and Feature Scaling (StandardScaler).

    - Interactive Web Interface: A fully functional dashboard built with Streamlit for real-time user input and prediction.

    - Optimized Inference: Uses serialized model files (.h5 and .pkl) to ensure fast and efficient performance.



🛠️ Technologies Used

    - Python (Core Development)
    - Deep Learning: TensorFlow, Keras
    - Data Science: Pandas, NumPy, Scikit-Learn
    - Web Framework: Streamlit
    - Serialization: Pickle (for Encoders/Scalers), H5 (for Model)



⚙️ Installation

    Follow these steps to set up the environment:

        1. Clone the repository:
            git clone https://github.com/your-username/AttritionShield.git

        2. Install the necessary dependencies:
            pip install -r requirements.txt



▶️ Usage

    To launch the application, run the following command in your terminal:
    streamlit run app.py



📂 Project Structure

    # app.py: The main Streamlit application for the web interface.
    # prediction.ipynb: Jupyter notebook for model testing and validation.
    # experiments.ipynb: Documentation of data cleaning and model training.
    # model.h5: The trained Artificial Neural Network model.
    # scaler.pkl: Serialized Standard Scaler for feature normalization.
    # label_encoder_gender.pkl: Encoder for categorical gender data.
    # onehot_encoder_geo.pkl: Encoder for geographical location data.
    # requirements.txt: List of required Python libraries.

    


