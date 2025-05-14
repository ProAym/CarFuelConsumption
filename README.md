# 🚗 Car Fuel Consumption Prediction from Images

## Overview
This project uses deep learning techniques to **predict car fuel consumption from exterior vehicle images**, providing a vision-based approach to vehicle efficiency assessment.  
It leverages **CNNs and transfer learning (VGG16, MobileNetV2)** to deliver a fast, scalable alternative to traditional methods.

---

## 🔑 Key Features

- **Model Architectures:**
  - Custom CNN
  - Fine-tuned **VGG16** and **MobileNetV2** using transfer learning

- **Dataset:**
  - **2,970 car images** labeled with actual fuel consumption data
  - Applied **data augmentation** to improve model robustness

- **Performance Metrics:**
  - Mean Squared Error (MSE)
  - Mean Absolute Error (MAE)
  - Root Mean Squared Error (RMSE)
  - R-Squared (R² Score)

---

## 🚀 Results

| Model                   | MSE     | MAE     | RMSE    | R² Score |
|-------------------------|---------|---------|---------|----------|
| Custom CNN               | 4.0386  | 0.4504  | 2.0096  | 0.6074   |
| Fine-tuned VGG16         | 3.777   | 0.4346  | 1.9434  | 0.6328   |
| Fine-tuned MobileNetV2   | 2.9364  | 0.3906  | 1.7136  | 0.7145   |

✅ **MobileNetV2 (Fine-tuned)** achieved the best performance with an **MAE of 0.3906** and **R² of 0.7145**, outperforming both the custom CNN and VGG16.

---

## 💡 Highlights

- Demonstrated that **transfer learning significantly boosts performance** on visual regression tasks.
- Showcased the potential for **data-driven vehicle efficiency assessments** using images alone.
- Provided a **cost-effective, scalable, and automated solution** for fuel consumption estimation.

---

## 🛠 Tech Stack

- **Languages & Frameworks:** Python, TensorFlow, Keras
- **Libraries:** NumPy, Matplotlib, Scikit-learn, etc.
