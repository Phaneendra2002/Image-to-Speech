# Image-to-Speech

🖼️🔊 Image to Speech using Artificial Intelligence
📌 Project Overview
This project presents an assistive technology solution for visually impaired individuals. It captures an image, generates a textual description of the scene using deep learning, and then converts the text into speech using the Google Text-to-Speech (gTTS) API.

👥 Team Members
B Phaneendra Kumar Suryadevara (20BCE0618)

Manas Jati (20BDS0223)

Hrithik Ram J (20BDS0226)

🧠 Motivation
Over 2.2 billion people worldwide experience visual disabilities. Our solution aims to empower them with greater independence in daily activities by converting the visual environment into spoken words.

🎯 Objectives
Develop a deep learning-based image captioning model.

Convert the generated description into audio.

Provide a simple and intuitive interface for visually impaired users.

🔧 Tools & Technologies
Python

TensorFlow / Keras

ResNet50 (for image feature extraction)

RNN / LSTM (for caption generation)

gTTS (Google Text-to-Speech)

Matplotlib (for displaying results)

IPython Audio (for playing sound)

⚙️ How It Works
Image Feature Extraction:
Uses ResNet50 CNN to convert the image into a feature vector.

Caption Generation:
A trained RNN model generates a caption from the extracted features.

Speech Synthesis:
The gTTS API converts the generated text into speech and plays the audio.

📂 Project Structure
VisTellCode.ipynb – Main notebook for training, prediction, and audio output.

Images/ – Directory containing sample images for testing.

final_report.pdf – Detailed documentation of the project architecture, literature survey, and results.

🖼️ Sample Output
csharp
Copy
Edit
Caption: "a man riding a skateboard on a street"
[Image is shown]
[Audio playback of caption]
📈 Future Enhancements
Enable real-time camera input instead of static image upload.

Add face recognition to connect detected faces with known contacts.

Implement advanced techniques like attention mechanisms and Beam Search.

Expand the training dataset for better generalization.

Evaluate using BLEU Score and reduce overfitting via cross-validation.

📚 References
Andrej Karpathy & Li Fei-Fei: Deep Visual-Semantic Alignments

D. Bahdanau, K. Cho, Y. Bengio: Attention-based NMT

Research on MLP-based quantization, CNN optimization, and object tracking.

