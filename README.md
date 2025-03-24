Neural Style Transfer (NST):
This project implements Neural Style Transfer (NST) using a pre-trained VGG-19 model in PyTorch. NST is a deep learning technique that applies the artistic style of one image to another while preserving the content.

Features:
1. Uses VGG-19 for feature extraction
2. Transfers artistic style from one image to another
3. Supports GPU acceleration (CUDA) for faster processing
4. Saves and displays the generated stylized image

Tech Stack:
1. Python
2. PyTorch
3. OpenCV (cv2)
4. Matplotlib

How It Works:
1. Load a content image and a style image.
2. Extract content and style features using a pre-trained VGG-19 model.
3. Optimize a copy of the content image to match the style features.
4. Save and display the final stylized image.
