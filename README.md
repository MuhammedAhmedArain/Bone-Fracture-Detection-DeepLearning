# 🦴 Bone Fracture Detection using Deep Learning

A deep learning–based system for detecting bone fractures from X-ray images using a custom CNN model (built from scratch) and an interactive Gradio web UI.

✨ Features

🔧 Custom CNN architecture (not pretrained)
📦 YOLO-V8 annotated dataset used for training
🔍 Training / Validation / Testing dataset splits
🌐 Gradio UI for easy user interaction
💾 Exports both .h5 and .pkl model formats
🔁 Fully reproducible code and workflow

📊 Model Details
Component	Description
Training Split	70%
Validation Split	20%
Testing Split	10%
Architecture	Custom CNN (Conv2D + MaxPooling + Dropout + Dense layers)

## 🚀 How to Run
Option 1 — Google Colab

Open the project notebook (app.py) in Google Colab

Upload the model file: cnn_bone_fracture_model.h5

Run all cells to launch the Gradio interface

Option 2 — VS Code / Local Machine
1. Install Dependencies
pip install gradio tensorflow numpy pillow

2. Run the Application
python app.py


<img width="1915" height="839" alt="image" src="https://github.com/user-attachments/assets/fb206239-a51c-4898-a579-2ab0ea203442" />

##

<img width="1907" height="853" alt="image" src="https://github.com/user-attachments/assets/fb371ecb-14e4-4b44-b254-9b092f9ac014" />

