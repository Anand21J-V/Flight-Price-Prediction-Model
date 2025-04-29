# ✈️ Flight Price Prediction Model

## 📌 Overview

This project aims to predict flight ticket prices using machine learning techniques. By analyzing various features related to flights, the model provides price estimations to assist users in making informed booking decisions. The application is built using Python and Flask, offering a user-friendly web interface for input and output. 

## 🧠 Features

- **Machine Learning Model**: Utilizes the K-Nearest Neighbors (KNN) algorithm for regression tasks.
- **Web Interface**: Built with Flask, allowing users to input flight details and receive price predictions.
- **Model Training Notebook**: Includes a Jupyter Notebook (`model_training.ipynb`) detailing the data preprocessing, model training, and evaluation processes.
- **Pre-trained Model**: A serialized KNN model (`flight_knn.pkl`) is provided for immediate use. ([sairasmi/flight-price-prediction - GitHub](https://github.com/sairasmi/flight-price-prediction?utm_source=chatgpt.com))

## 🗂️ Project Structure

```

Flight-Price-Prediction-Model/
├── static/
│   └── css/
├── templates/
│   └── [HTML templates for the web interface]
├── .gitignore
├── LICENSE
├── README.md
├── app.py
├── flight_knn.pkl
├── model_training.ipynb
└── requirements.txt
```


## 🚀 Getting Started

### Prerequisites

- Python 3.x
- pip (Python package installer) ([Mandal-21/Flight-Price-Prediction - GitHub](https://github.com/Mandal-21/Flight-Price-Prediction?utm_source=chatgpt.com))

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Anand21J-V/Flight-Price-Prediction-Model.git
   cd Flight-Price-Prediction-Model
   ```


2. **Create a virtual environment (optional but recommended)**:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```


3. **Install the required packages**:

   ```bash
   pip install -r requirements.txt
   ```


## 🧪 Usage

1. **Run the Flask application**:

   ```bash
   python app.py
   ```


2. **Access the web interface**:

   Open your web browser and navigate to `http://127.0.0.1:5000/`.

3. **Input Flight Details**:

   Enter the required flight information as prompted on the web page.

4. **Get Prediction**:

   Submit the form to receive the predicted flight price based on the input details.

## 📊 Model Training

The `model_training.ipynb` notebook provides a comprehensive walkthrough of the data preprocessing steps, feature engineering, model training, and evaluation metrics. It serves as a valuable resource for understanding the underlying mechanics of the prediction model.

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 🙏 Author

Anand Kumar Vishwakarma
