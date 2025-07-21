# 🧠 MNIST Digit Recognizer - Streamlit + PyTorch

A web-based digit recognition app that allows users to draw a digit (0–9) on a canvas, and predicts the digit using a custom Convolutional Neural Network (CNN) built with PyTorch.

## 🚀 Features

- Draw any digit using a digital canvas
- Real-time digit classification using a CNN
- Built with PyTorch and deployed using Streamlit
- GPU-enabled inference for faster performance

## 🛠️ Tech Stack

- **Frontend**: [Streamlit](https://streamlit.io/)
- **Model**: CNN built with [PyTorch](https://pytorch.org/)
- **Canvas Drawing**: [`streamlit-drawable-canvas`](https://github.com/andfanilo/streamlit-drawable-canvas)

## 📁 Project Structure

├── app.py # Streamlit web app
├── model/
│ └── mnist_v0.pth # Trained PyTorch model weights
└── README.md # Project documentation
