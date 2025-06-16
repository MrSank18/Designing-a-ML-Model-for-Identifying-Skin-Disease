# Skin Disease Detection & Diagnosis Using Machine Learning

This project is a **Skin Disease Classification Web Application** that uses deep learning to predict various skin diseases from images. The application is built with **Flask**, leveraging a pre-trained TensorFlow model for classification. It provides a user-friendly interface for uploading images and receiving disease predictions.

## Features
- **Disease Detection**: Identifies skin diseases from an uploaded image with high accuracy.
- **Deep Learning**: Powered by TensorFlow and a convolutional neural network model.
- **Interactive UI**: Built with Flask, styled using CSS, and includes responsive JavaScript functionality.
- **Disease Classes**:
  - Cellulitis
  - Impetigo
  - Athlete's Foot
  - Nail Fungus
  - Ringworm
  - Cutaneous Larva Migrans
  - Chickenpox
  - Shingles


## Project Structure
```plaintext
  ├── static/
  │   ├── style.css
  │   └── index.js
  ├── templates/
  │   └── index.html
  ├── main.py
  ├── Skin_Disease_Classification.ipynb
  ├── skin_disease_model.h5
  └── README.md
```

- **static/**: Contains `style.css` and `index.js` files for styling and interactivity.
- **templates/**: Contains the `index.html` file for rendering the web interface.
- **main.py**: The Flask application script.
- **Skin_Disease_Classification.ipynb**: Notebook detailing model creation and training.
- **skin_disease_model.h5**: Trained model for skin disease classification.

## Installation and Usage
### Prerequisites
- Python 3.x
- TensorFlow
- Flask
- PIL (Pillow)

  
### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/skin-disease-classification.git
   cd skin-disease-classification
2. Install dependencies:
   ```bash
   pip install -r requirements.txt

### Running the Application
1. Start the Flask server:
  ```bash
  python main.py
```
2. Open your browser and navigate to http://127.0.0.1:5000.

3. Upload an image to predict the skin disease.

### Model
  Model is not able to upload here due to large size please go through the ibpy file to train model and use it 

### Dataset
  use dataset from Kaagle
