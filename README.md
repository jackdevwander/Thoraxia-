# Advancing Chest Abnormality Detection  
## Using Deep Learning Innovations for Enhanced Diagnostic Precision  

Members: Namratha S, Hitha K, Fathima Thaskeen, Gahana Shetty, Dr Sannidhan M S
This project proposes a hybrid **Quantum-Classical Convolutional Neural Network (QCNN)** for detecting and assessing multiple diseases using **CT scans and Lung X-rays**. By integrating **Quantum Fourier Transform (QFT) layers** with classical CNNs, it leverages **quantum computing** for enhanced accuracy and generalization.  

Trained on a diverse dataset covering **COVID-19, Pneumonia, and Tuberculosis**, the model outperforms traditional CNNs in both **disease classification and severity assessment**, aiding clinical decision-making. This approach improves **diagnostic precision** and offers insights into **disease progression**, advancing medical imaging and healthcare.  

## Process Flow  
<p align="center">  
<img src="https://github.com/user-attachments/assets/2eaf4116-ba48-4dd5-b0e4-227403a0c7f1" alt="Process Flow">  
 

</p>  

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
1. **Download the project files** from [Google Drive](https://drive.google.com/drive/folders/1bpR9vPiv8w8R799NpsSn9yXdKQtdgrHS?usp=sharing).
3. **Unzip the downloaded files**.  
4. Ensure the following folder structure:  
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
   
## Datasets Used  
- **COVID-19**: [SARS-CoV-2 CT-Scan Dataset](https://www.kaggle.com/datasets/plameneduardo/sarscov2-ctscan-dataset)  
- **Pneumonia**: [Chest X-ray Pneumonia Dataset](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)  
- **Tuberculosis**: [TB Chest X-ray Dataset](https://www.kaggle.com/datasets/tawsifurrahman/tuberculosis-tb-chest-xray-dataset)  

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

## Visual Gallery 
Here we've shown some sample X-ray/CT scan images and their segmented versions for each dataset
<p align="center">  
<img src="https://github.com/user-attachments/assets/5b7cde86-b830-4960-bb05-790e2df1a043" alt="Visual Gallery">  
</p>  
