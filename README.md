# DermNET_Image_Classification

🩺 Skin Disease Classification with ResNet152
🔬 Description
This project aims to classify 10 different skin diseases using deep learning techniques and transfer learning with ResNet152. The model is trained on a custom image dataset of dermatological conditions and optimized using class balancing and learning rate scheduling to improve performance on imbalanced data.

📌 Key Features
✅ Transfer Learning with ResNet152 pretrained on ImageNet

⚖️ Automatic class weight computation to address class imbalance

🧠 Fine-tuning last 50 layers for domain-specific learning

📈 Visualization of training/validation accuracy & loss

📊 Confusion matrix for detailed performance analysis

💾 Trained model saved in both .keras and .h5 formats

📂 Dataset structure:

bash
Copy
Edit
/skin_diseases_images/IMG_CLASSES/
  ├── Eczema/
  ├── Viral Infections/
  ├── Melanoma/
  └── ...
🧪 Classes:
Eczema

Viral Infections

Melanoma

Atopic Dermatitis

Basal Cell Carcinoma

Melanocytic Nevi

Keratosis-like Lesions

Psoriasis & Lichen Planus

Seborrheic Keratoses

Fungal Infections

🛠️ Technologies Used
Python

TensorFlow / Keras

NumPy, Matplotlib, Seaborn

scikit-learn

