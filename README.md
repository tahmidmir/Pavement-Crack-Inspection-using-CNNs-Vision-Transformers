# 🛣 Pavement Crack Inspection using CNNs & Vision Transformers  
### 🔍 Asphalt Crack Detection with Deep Learning (CNN & ViT)  
---

## 📌 Description   
Inspecting and identifying **asphalt surface cracks** is essential for **enhancing road safety**.  
This project leverages **deep learning** to automatically detect road cracks.  
✅ **Advantages:**  
- Reduced cost and time for road inspections  
- Higher accuracy compared to traditional methods  
- Capability for large-scale analysis  

---

## 📌 Methods Used  

### 1️⃣ **Convolutional Neural Networks (CNNs)**  
✔️ Traditional models in **computer vision**  
✔️ Extraction of local features such as edges and crack textures  
✔️ Tested models: **U-Net**, **DeepLabV3+**  

### 2️⃣ **Vision Transformers (ViTs)**  
✔️ Latest technique in **image processing**  
✔️ Utilization of **Self-Attention** for better crack understanding  
✔️ Tested models: **Segformer**, **UperNet-Swin Transformer**  

---

## 📦 Installation and Setup  

### Dependencies  
**Libraries used in this project:** 
- PIL (Pillow) 
- collections.Counter  
- keras.preprocessing.image 
- scikit-learn (sklearn)  
- tensorflow.keras   
- cv2 (OpenCV) 
- matplotlib 
- numpy 
- pandas  
- plotly.express  
- seaborn 
- tensorflow  
- tensorflow_addons 
- visualkeras 
- warnings  


---
### Run the Notebook  
```bash
jupyter notebook sentiment-analysis-bert-xai.ipynb
```
---

## 📊 Sample Results  

| Model | Accuracy | Advantages | Disadvantages |
|------|------------|---------|---------|
| **U-Net** | 85% | High accuracy for clear cracks | Requires more data |
| **DeepLabV3+** | 88% | Better performance on irregular edges | Slower speed |
| **Segformer** | 91% | Precise detection of crack textures | Heavier computations |

---


- If you have suggestions for improving the project, please submit a **Pull Request**.  
- To report issues, please open an **Issue**.  

---

