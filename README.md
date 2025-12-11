Neural Style Transfer (NST) – PyTorch (With Colab Support)

This project implements Neural Style Transfer (NST) using PyTorch. It allows you to blend the content of one image with the style of another using VGG-19 feature representations. The repository also supports Fast Style Transfer using a pre-trained transformer network.
The code is fully compatible with Google Colab, including automatic image upload and saving the stylized output.

✨ Features

Full Neural Style Transfer (Gatys et al.) implementation
Uses VGG-19 for feature extraction
Supports both slow/high-quality NST and fast style transfer using a transformer network
Automatic image upload when running in Google Colab
Handles CUDA automatically if available
Gram matrix computation, style/content loss layers, and image normalization included
Easy to modify, extend, or fine-tune

📘 How It Works

You provide:

A content image
A style image
The model optimizes a new image that:
Preserves the structure of the content image
Adopts the texture, color, and brush strokes of the style image

▶️ Run in Google Colab

Open the project notebook in Google Colab:

https://colab.research.google.com/drive/1sX_b8UGpQhPYyfJQe_q8EPuLiw92tXJK?usp=sharing
