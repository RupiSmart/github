# RupiSmart Project

![PMI](https://github.com/user-attachments/assets/ba3a50ae-ce37-4bb2-9e05-86b6269d8721)

RupiSmart is an integrated project that leverages Machine Learning, Mobile Development, and Cloud Computing technologies to provide solutions for detecting Indonesian currency for visually impaired users. This project encompasses three main aspects: denomination classification, authenticity verification, and the development of a mobile application connected to cloud services.

---

## 👑 **Team Member**

| Name                   | Student ID  | Learning Path            |
|------------------------|-------------|--------------------------|
| Adnan Naufal Ardana   | M409B4KY0125| Machine Learning - 61    |
| Putri Angel Saraswati | M315B4KX3515| Machine Learning - 75    |
| Fahria Salsabilla     | M265B4KX1352| Machine Learning - 19    |
| Muhammad Agung Faizal | C171B4KY2695| Cloud Computing - 21     |
| Nurul Aini Komarudin  | C299B4KX3441| Cloud Computing - 35     |
| Ramdhan Rayina        | A171B4KY3682| Mobile Development - 38  |
| Iwan Fauzy            | A171B4KY2029| Mobile Development - 45  |


---

## 📜 **Key Features**

1. **Currency Denomination Classification**
   - Identifies the denomination of Indonesian coins and banknotes using machine learning models.
   - Integrates pretrained EfficientNetB0 model for robust features.

2. **Currency Authenticity Verification**
   - Detects the authenticity of currency using a custom CNN architecture.
   - Provides performance metrics such as accuracy and validation for each class.

3. **Connected Mobile Application**
   - Android-based application with text-to-speech support and camera integration for optimal user experience.

4. **Cloud Infrastructure**
   - Utilizes Google Cloud Platform for scalable API services and cloud architecture.

---

## 📂 **Repository Structure**

### 1. **Machine Learning**
   - Implementation of models for currency denomination classification and authenticity verification.
   - Dataset:
     - **Denomination**: 12 classes with more than 790 images per class.
     - **Authenticity**: 2 classes with a total of 154 images.
   - Model architecture:
     - **EfficientNetB0** for denomination classification.
     - **Custom CNN** for authenticity verification.
   - [Link to Machine Learning repository](https://github.com/RupiSmart/Machine-Learning)

### 2. **Mobile Development**
   - Kotlin-based mobile application with the following technologies:
     - **Android Studio**
     - **Camerax** for capturing images.
     - **Retrofit2** for API integration.
     - **Text-to-Speech** for accessibility.
   - [Link to Mobile Development repository](https://github.com/RupiSmart/Mobile-Development)

### 3. **Cloud Computing**
   - API for integration between mobile applications and machine learning models.
   - Uses Google Cloud architecture for high performance and scalability.
   - [Link to Cloud Computing repository](https://github.com/RupiSmart/Cloud-Computing)

---

## 🚀 **Installation and Usage Guide**

### **1. Machine Learning**
1. Clone the repository:
   ```bash
   git clone https://github.com/RupiSmart/Machine-Learning.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the model for denomination classification or authenticity verification:
   - Denomination classification:
     ```bash
     python model_denomination.ipynb
     ```
   - Authenticity verification:
     ```bash
     python model_authenticity.ipynb
     ```

### **2. Mobile Development**
1. Clone the repository:
   ```bash
   git clone https://github.com/RupiSmart/Mobile-Development.git
   ```
2. Open the project in Android Studio.
3. Build and run the application on an emulator or physical device.

### **3. Cloud Computing**
1. Clone the repository:
   ```bash
   git clone https://github.com/RupiSmart/Cloud-Computing.git -b main
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the API server.
4. This Branch model-backend. Installation :
   
```
git clone https://github.com/RupiSmart/Cloud-Computing.git -b model-backend
```
5. Install requirements
```
pip install -r requirements.txt
```
---

## 🎯 **Future Development Plans**
- Expand the dataset for better generalization.
- Improve real-time inference for mobile applications.
- Integrate ensemble models for enhanced performance.
- Add cross-platform support.

---

For more detailed information, please refer to each repository or contact our development team.

---

Happy coding! 🚀
