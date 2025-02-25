# Advancing Chest Abnormality Detection  
## Using Deep Learning Innovations for Enhanced Diagnostic Precision  

This project proposes a hybrid **Quantum-Classical Convolutional Neural Network (QCNN)** for detecting and assessing multiple diseases using **CT scans and Lung X-rays**. By integrating **Quantum Fourier Transform (QFT) layers** with classical CNNs, it leverages **quantum computing** for enhanced accuracy and generalization.  

Trained on a diverse dataset covering **COVID-19, Pneumonia, and Tuberculosis**, the model outperforms traditional CNNs in both **disease classification and severity assessment**, aiding clinical decision-making. This approach improves **diagnostic precision** and offers insights into **disease progression**, advancing medical imaging and healthcare.  

## Process Flow  
![Process Flow](https://github.com/user-attachments/assets/5818a73a-76dd-44c2-8f7a-8c5c880e7122)  

## Technologies Used  
- Python  
- NumPy  
- Pandas  
- TensorFlow  
- OpenCV  
- Qiskit  

## Installation  
To install the required libraries, run the following command:  
```sh  
pip install -r requirements.txt  
```

## Usage  
1. **Download the project files** from the [[Google Drive link](https://drive.google.com/drive/u/1/folders/1bpR9vPiv8w8R799NpsSn9yXdKQtdgrHS)].
2. **Unzip the downloaded files**.  
3. Ensure the following folder structure:  
   ```
   Thoraxia/
   ├── flask_session/
   ├── static/
   ├── templates/
   ├── venv/
   ├── app.py
   ├── covid_qcnn_model.h5
   ├── model_qcnn.h5
   ├── pneumonia_qcnn_model.h5
   ├── requirements.txt
   ```  

## How to Run  
1. **Activate the virtual environment:**  
   ```sh  
   source venv/bin/activate  # On macOS/Linux
   venv\Scripts\activate  # On Windows
   ```  
2. **Run the Flask application:**  
   ```sh  
   python app.py  
   ```  
3. **Access the application** in your browser at:  
   ```
   http://127.0.0.1:5000/
   ```
   

## Datasets Used  
- **COVID-19**: [SARS-CoV-2 CT-Scan Dataset](https://www.kaggle.com/datasets/plameneduardo/sarscov2-ctscan-dataset)  
- **Pneumonia**: [Chest X-ray Pneumonia Dataset](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)  
- **Tuberculosis**: [TB Chest X-ray Dataset](https://www.kaggle.com/datasets/tawsifurrahman/tuberculosis-tb-chest-xray-dataset)  

