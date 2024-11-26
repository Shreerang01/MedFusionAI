
# MedFusion AI 🚀  
**Multi-Disease Diagnostic Platform**  

MedFusion AI is the Final Year Capstone Project developed under the Department of Electrical and Electronics Engineering at MIT World Peace University. This platform integrates AI-driven diagnostics with edge computing, hosted on a Raspberry Pi, to provide affordable and accessible disease detection for conditions such as COVID-19, Diabetes, Brain Tumors, and Breast Cancer.

Designed for underserved and remote regions, MedFusion AI leverages individual machine learning models tailored to each disease, offering precise and efficient health assessments. With a focus on portability, privacy, and offline functionality, the platform addresses critical gaps in healthcare accessibility and early detection.

 

## Features 🌟  
- **Multi-Disease Detection**: AI models tailored for specific conditions.  
- **Offline Operation**: Works seamlessly in resource-constrained areas without the need for constant internet connectivity.  
- **Privacy-Preserving**: All data is processed locally on the Raspberry Pi.  
- **User-Friendly Interface**: Accessible dashboard for healthcare providers and non-specialists.  

---

## Demonstartion Video

https://drive.google.com/file/d/1ei3L-BUcX0cKL7b14JdlOjeU9g1-I02G/view?usp=sharing 

---

## Table of Contents  
- [System Overview](#system-overview)  
- [Architecture](#architecture)  
- [Setup Instructions](#setup-instructions)  
- [Usage](#usage)  
- [Results and Performance](#results-and-performance)  
- [Future Scope](#future-scope)  
- [Contributors](#contributors)  

---

## System Overview 🛠️  
**Objective**: To democratize healthcare diagnostics with an AI-powered platform that bridges healthcare gaps in remote areas.  

Key functionalities:  
- Raspberry Pi 4 -powered diagnostic platform.  
- Disease detection models trained for medical imaging and health metrics.  
- Real-time results displayed in a unified web interface.  

---

## Architecture 🏗️  
### System Components:  
1. **Raspberry Pi 4 Model B**: The core hardware for hosting the platform.  
2. **Flask Backend**: Handles user requests, processes inputs, and serves predictions.  
3. **Machine Learning Models**:  
   - **CNN** for image-based diagnostics (COVID-19, Brain Tumors).  
   - **Random Forest** for health metrics (Diabetes, Breast Cancer).  
4. **Data Preprocessing**: Ensures input compatibility with models.  
5. **User Interface**: Intuitive web-based dashboard for diagnostics and reporting.  

### Workflow:  
1. User uploads medical data (images or metrics).  
2. Data is preprocessed to meet model requirements.  
3. Disease-specific AI models generate predictions.  
4. Results are displayed in real-time through the interface.  

---

## Setup Instructions 🖥️  
### Prerequisites:  
- **Hardware**: Raspberry Pi 4 (4GB RAM), SD Card (32GB+), Power Adapter.  
- **Software**: Python 3.6+, Flask, TensorFlow/Keras, scikit-learn, OpenCV.  

### Steps:  
1. Flash the Raspberry Pi OS using Raspberry Pi Imager.  
2. Install Python and required libraries.  
   ```bash
   pip install flask tensorflow keras scikit-learn opencv-python
   ```  
3. Clone this repository:  
   ```bash
   git clone https://github.com/<your-repo>/MedFusionAI.git
   cd MedFusionAI
   ```  
4. Deploy the Flask application:  
   ```bash
   python app.py
   ```  
5. Access the platform at `http://<your-device-ip>:5000`.  

---

## Usage 📋  
1. Launch the platform and navigate to the dashboard.  
2. Select the disease module (COVID-19, Diabetes, etc.).  
3. Upload the required data (e.g., Chest X-ray for COVID-19).  
4. Submit the data and view the diagnostic results.  

---

## Results and Performance 📈  
- **COVID-19**: 96.4% accuracy using CNN.  
- **Diabetes**: 76.62% accuracy using Random Forest.  
- **Brain Tumors**: 90% accuracy using CNN.  
- **Breast Cancer**: 94.15% accuracy using Random Forest.  

---

## Future Scope 🌟  
- Expand to detect more diseases like tuberculosis and malaria.  
- Integrate real-time monitoring with wearable devices.  
- Enhance UI with multi-language support.  
- Include cloud storage for data backup and remote diagnostics.  

---

## Contributors 🤝  
- **Mukund Narsaria**: Diabetes Detection, Frontend Development, Integration.  
- **Atharv Yadav**: COVID-19 Detection, Model Optimization.  
- **Shreerang Mhatre**: Brain Tumor, Breast Cancer Detection Models and Raspberry Pi Deployment.  

**Project Guide**: Dr. Netra Lokhande  


