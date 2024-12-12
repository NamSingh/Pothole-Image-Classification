# Pothole Image Classification: Zindi MIIA Challenge

This project implements **image classification** to detect potholes using machine learning models. Developed as part of the [Zindi MIIA Pothole Image Classification Challenge](https://zindi.africa/competitions/miia-pothole-image-classification-challenge), this solution aims to automate the detection of road damage, reducing the time and cost of maintenance while improving road safety. The final solution leverages a state-of-the-art image classification model, achieving **6th place** as *Team Bathurst* with the **MaxViT Tiny 384x384** model.

## 📑 **Table of Contents**

1. [Business Value and Real-World Applications](#-business-value-and-real-world-applications)
2. [Technologies Used](#-technologies-used)
3. [What the Code Does](#-what-the-code-does)
4. [How to Run the Code](#-how-to-run-the-code)
5. [Key Highlights](#-key-highlights)
6. [References](#-references)

---

## 🌍 **Business Value and Real-World Applications**

Potholes are a significant contributor to road accidents and vehicle damage, resulting in extensive repair costs and safety risks. In South Africa, **5% of deaths** are attributed to poor road maintenance, highlighting the critical need for effective solutions. This project demonstrates how machine learning can deliver real-world impact through efficient and accurate road damage detection.

### **Key Benefits:**
- **Enhanced Road Safety**: By identifying road damage early, authorities can take timely action to prevent accidents and reduce fatalities caused by poor road conditions.  
- **Optimized Maintenance Costs**: Targeted detection reduces unnecessary inspections and ensures efficient resource allocation.  
- **Better Utilization of Worker Hours**: Automating pothole detection allows maintenance workers to focus on more strategic and impactful tasks, improving overall productivity.  

---

## 🛠️ **Technologies Used**

- **Python**
- **Deep Learning Frameworks**: PyTorch
- **Convolutional Neural Network (CNN) Architectures**: 
  - VGG16  
  - ResNet (34, 50, 152)  
  - EfficientNetB4  
  - ViT_BASE  
  - MaxViT Tiny 384x384 (final submission model)

---

## 🔎 **What the Code Does**

The project is organized into the following key components:

1. **Data Preprocessing**:  
   - Reads, resizes, and normalizes image data for input into the models.  
   - Splits data into training, validation, and test sets to ensure robust evaluation.  

2. **Model Implementation**:  
   - Includes implementations of **VGG16** and **ResNet** architectures in the provided codebase.  
   - Trains and fine-tunes various models using techniques like transfer learning.  

3. **Evaluation**:  
   - Assesses models using metrics like accuracy, precision, recall, and F1 score.  
   - Logs performance for different hyperparameter configurations to determine the optimal setup.  

4. **Submission**:  
   - Outputs predictions in the required format for Zindi's competition leaderboard.  

---

## 🚀 **How to Run the Code**

1. **Clone the repository**:  
   ```bash
   git clone https://github.com/NamSingh/Pothole-Image-Classification.git
   cd Pothole-Image-Classification
   ```

2. **Run the Jupyter Notebook**:  
   Open and execute `ResNetPotholeDetection.ipynb` to preprocess data, train models, and evaluate results.  

3. **Modify parameters (optional)**:  
   Update the notebook to try different architectures or hyperparameters.  

*Note:*  
   This repository does not include the exact code that achieved a **6th place finish** in the competition. However, it provides a well-structured and closely related framework, which, with modifications, can achieve similar results. The code here focuses on **ResNet** and **VGG** models, while the competition submission used **MaxVIT_tiny_384x384** for the final results.

---

## ✨ **Key Highlights**

- **6th Place Finish**: Achieved **6th place** as *Team Bathurst* with the **MaxViT Tiny 384x384** model on the Zindi leaderboard.  
- **Model Variety**: Experimented with multiple architectures, including VGG16, ResNet variations, EfficientNetB4, and ViT_BASE.  

---

## 📜 **References**

- Zindi Competition Page: [MIIA Pothole Image Classification Challenge](https://zindi.africa/competitions/miia-pothole-image-classification-challenge)