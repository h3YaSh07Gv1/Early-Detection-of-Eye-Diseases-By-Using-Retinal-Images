# Eye Disease Classification Web App

This project uses a deep learning model based on ResNet9 to classify retinal images into different eye disease categories. It includes a Streamlit web interface and a Jupyter Notebook for model development.

## 📁 Project Structure

* `app2.py`: Streamlit application to run the web interface.
* `prediction.py`: Contains the ResNet9 model definition and prediction utilities.
* `Eye_disease_classification2.ipynb`: Jupyter notebook for model training and evaluation.
* `final.pth`: Trained model weights (must be placed in the same directory).
* `requirements.txt`: List of dependencies.

## 🚀 Setup Instructions

### 1. Clone the Repository

```bash
git clone <your-repo-url>
cd <repo-directory>
```

### 2. Create a Virtual Environment (optional but recommended)

```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Ensure Model File is Present

Make sure `final.pth` (trained model file) is in the same directory as `prediction.py`.

## 🧰 Run the Jupyter Notebook

Use the notebook for training or further experimentation:

```bash
jupyter notebook Eye_disease_classification2.ipynb
```

## 🌐 Run the Streamlit App

To launch the web application:

```bash
streamlit run app2.py
```

This will open a web interface in your default browser to upload images and view predictions.

## ⚙️ Requirements

* Python 3.9+
* PyTorch
* Torchvision
* Streamlit
* NumPy
* Matplotlib

All dependencies are listed in `requirements.txt`.

## 🧠 Model

The project uses a ResNet9-based CNN for image classification, trained on retinal image datasets.
