🩺 Face Mask Detection


📌 Overview

Deep learning project to detect With Mask 😷 vs Without Mask 😐 using:

CNN (from scratch)

MobileNetV2 (Transfer Learning)

ResNet50 (Transfer Learning)



📂 Dataset

Organized into Train / Validation / Test.

Two classes: WithMask, WithoutMask.

🛠️ Tech Stack

Python, TensorFlow/Keras

OpenCV, NumPy, Pandas

Matplotlib, Seaborn, scikit-learn



⚙️ Workflow

Load & preprocess dataset.

Apply augmentation (flip, rotate, zoom).

Train models (CNN, MobileNetV2, ResNet50).

Evaluate with accuracy, confusion matrix, classification report.

Save best model → Models/best_model.keras.



📊 Results (example)
Model	Accuracy
CNN	 0.9667  
MobileNetV2	0.9980  
ResNet50	 0.9980

🏆 Best performing model: MobileNetV2 with 0.9980 accuracy


▶️ Run
pip install -r requirements.txt
python face_mask_detection.py


