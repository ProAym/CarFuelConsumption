🚗 Car Fuel Consumption Prediction from Images
Overview
Developed a deep learning-based regression model to predict car fuel consumption directly from exterior vehicle images. This project explores a vision-based approach for vehicle energy efficiency assessment, offering a scalable and cost-effective alternative to traditional testing methods.

Key Features
Model Architectures:

Custom CNN

Fine-tuned VGG16 and MobileNetV2 using transfer learning

Dataset:

Built a custom dataset of 2,970 car images labeled with fuel consumption data

Applied data augmentation for improved generalization

Performance Metrics:

MSE, MAE, RMSE, R² Score

Results
Best performer: MobileNetV2 (Fine-tuned)

MAE: 0.3906

R² Score: 0.7145

Outperformed custom CNN (R² 0.6074) and fine-tuned VGG16 (R² 0.6328)

Model	MSE	MAE	RMSE	R² Score
Custom CNN	4.0386	0.4504	2.0096	0.6074
Fine-tuned VGG16	3.777	0.4346	1.9434	0.6328
Fine-tuned MobileNetV2	2.9364	0.3906	1.7136	0.7145

🔥 Proved the effectiveness of transfer learning for regression tasks on visual data, offering a faster, automated tool for fuel consumption estimation.

Tech Stack
Python, TensorFlow, Keras

Libraries: NumPy, Matplotlib, etc.
