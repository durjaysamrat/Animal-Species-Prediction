# 🐾 Animal-Species-Prediction  

[![Google Colab](https://img.shields.io/badge/Run%20on-Google%20Colab-orange?style=for-the-badge&logo=google-colab)](https://colab.research.google.com/drive/1ugpiSjrO1bSc2tjYMLsIfX9CAMTheghb?authuser=3)  

This project leverages the power of **YOLOv5** for object detection and classification to build a system that identifies animal species in real-world images. From collecting datasets to model training and deployment, the system is designed to provide robust and accurate predictions. 🦁🐘🐒  

---

## 🌟 Overview  

The **Animal Species Prediction System** uses the YOLOv5 deep learning framework to detect and classify multiple animal species in images. This project demonstrates the application of computer vision techniques for wildlife conservation, research, and monitoring.  

✨ **Highlights:**  
- Object detection and classification with YOLOv5.  
- Integration with a user-friendly interface.  
- Real-world image predictions with high accuracy.  

---

## 📂 Dataset  

The dataset includes images of 12 different animal species, such as:  
- 🐅 Tiger  
- 🦒 Giraffe  
- 🐻 Bear  
- 🦁 Lion  
- 🐘 Elephant  
- 🦌 Deer  
- 🐺 Wolf  
- 🐂 Bull  
- 🐒 Monkey  
- 🐆 Leopard  
- 🦏 Rhinoceros  
- 🦛 Hippo  

[**Dataset Link**](https://drive.google.com/drive/folders/1xBHb2l4Z70Z-oPXHR3QvZF3iaYZnSGx-?usp=sharing)  

**Example Predictions:**  
![pred_elephant](https://github.com/user-attachments/assets/aaf3398c-4309-49a7-90c8-ed9d96dcdcff)
| **Cattle** | **Monkey** |  
|-------------|------------|  

| ![pred_cattle](https://github.com/user-attachments/assets/ac37308f-db56-4006-a84a-84c7a566ff71) | ![pred_monkey](https://github.com/user-attachments/assets/87c1a867-3e6b-4fe6-873c-50a5f7d0245e) |  

---

## 🛠️ Data Preparation  

1. **Data Collection:** Images of various animal species were gathered and labeled with bounding boxes.  
2. **Data Splitting:** The dataset was split into **80% training** and **20% validation** sets.  
3. **Storage:** Prepared datasets were uploaded to Google Drive for seamless integration with the training pipeline.  

---

## 📊 Model Training  

The YOLOv5 model was trained with the following parameters:  
- **Image size:** 415  
- **Batch size:** 31  
- **Epochs:** 100  
- **Pre-trained weights:** `yolov5s`  

**Inference:**  
The model uses trained weights (`best.pt`) to detect multiple animal species in an image and outputs bounding boxes with class labels.  

---

## 🎯 Results  

The system achieved **high accuracy** in detecting and classifying animal species in real-world images. The predictions include bounding boxes and species labels for each detected animal, supporting multiple detections in a single image.  

---

## 🖼️ Display  

Detected images include bounding boxes with labels:  

- **Input Image:** Wildlife photograph  
- **Output:** Annotated image with detected species  
https://github.com/user-attachments/assets/31e7dcb6-65be-4801-ae7c-284e5de3778b

---

## 🐾 Conclusion  

This project showcases the potential of YOLOv5 for wildlife monitoring and research. Applications include:  
- Wildlife conservation  
- Animal behavior studies  
- Automated zoo monitoring systems  

**Future Work:**  
- Expand to more species for increased biodiversity coverage.  
- Improve model efficiency and deploy as a real-time system.  

---

## 🤝 Contributions  

Contributions are welcome! 🎉  
- Report issues or suggest features via [issues](https://github.com/durjaysamrat/Animal-Species-Prediction/issues).  
- Fork the repository, implement your ideas, and submit a pull request.  

---

## 📫 Connect  

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/durjay-samrat)  
[![GitHub](https://img.shields.io/badge/GitHub-%23121011?style=for-the-badge&logo=github&logoColor=white)](https://github.com/durjaysamrat)  

---

⭐ **If you find this project helpful, give it a star!**  
Let’s build smarter tools for wildlife conservation together! 🌍🐾  

---

Let me know if you'd like to make further adjustments or add more details. 😊
