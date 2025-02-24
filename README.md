# Object Detection Assistant System

## 📌 Overview
This project is an Object Detection Assistant that processes images, detects objects, and provides both visual and audio descriptions using machine learning models. The system leverages `Transformers`, `gTTS`, and `Gradio` for an interactive experience.

![App Preview](https://github.com/IbrahimAl-Labbad/Object-Detection-Assitant-System/blob/main/Screenshot%20From%202025-02-24%2017-12-17-1.png)

## 🚀 Features
- 📷 **Object Detection**: Detect objects in an uploaded image using `facebook/detr-resnet-50`.
- 🖼️ **Annotated Image**: Returns an image with bounding boxes around detected objects.
- 🔊 **Audio Description**: Generates an audio summary of detected objects using `gTTS`.
- 🌐 **User Interface**: Provides a simple and interactive UI using `Gradio`.

## 🛠️ Installation
Ensure you have Python installed, then install the required dependencies:
```bash
pip install -r requirements.txt
```
## 📂 Project Structure
```
📦 Object-Detection-Assistant-System
 ┣ 📜 Object_Detection_Assistant.ipynb  # Jupyter Notebook with implementation
 ┣ 📜 README.md                          # Project documentation
 ┣ 📜 requirements.txt                    # List of dependencies
```

## ▶️ Usage
Run the following command to launch the Gradio web interface:
```bash
python Object_Detection_Assistant.ipynb
```

## 🖥️ How It Works
1. Upload an image.
2. The model detects objects and highlights them with bounding boxes.
3. A natural language summary of detected objects is generated.
4. The summary is converted into speech using `gTTS`.

## 📌 Example Output
- **Input:** Image containing objects like a dog and a car.
- **Output Image:** The image with bounding boxes drawn around detected objects.
- **Audio Output:** "In this image, there is one dog and one car."


---
🚀 Developed by [Ibrahim Al-Labbad](https://github.com/IbrahimAl-Labbad)
