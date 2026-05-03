<img width="1280" height="853" alt="image" src="https://github.com/user-attachments/assets/24c7f759-e17c-46ff-a4e4-88e7f2d34f23" />



🖼️ NumPy Image Processing Engine
📌 Overview
This project demonstrates how core image processing operations can be implemented from scratch using NumPy, without relying on high-level image processing libraries.
The goal was to understand how images are represented as arrays and how transformations can be applied at the pixel level.

🚀 Features
Grayscale conversion
Brightness adjustment
Contrast enhancement
Image flipping (horizontal & vertical)
Image cropping
Blur using convolution
Edge detection using Sobel filters

🧠 Concepts Used
NumPy arrays (image as 3D matrix)
Broadcasting
Slicing and indexing
Convolution (kernel-based filtering)
Gradient-based edge detection

🛠️ Tech Stack
Python
NumPy
Matplotlib
SciPy

▶️ How to Run
Open the notebook in Google Colab or Jupyter Notebook
Upload an image file (e.g., .jpg, .png)
Run all cells sequentially

📊 Project Workflow
Load image → convert to NumPy array
Apply transformations (grayscale, brightness, contrast)
Perform spatial operations (flip, crop)
Apply convolution for blur
Detect edges using Sobel filters

💡 Key Learnings
Images are numerical data stored as multi-dimensional arrays
Pixel-wise operations can transform entire images efficiently
Broadcasting simplifies large-scale computations
Convolution is the foundation of many image processing techniques
Edge detection highlights areas of rapid intensity change

⚡ Challenges Faced
Slow performance using Python loops
Understanding convolution mechanics
Managing pixel value limits (0–255 range)

🚀 Future Improvements
Add more filters (sharpen, emboss)
Optimize convolution using full vectorization
Add interactive controls (sliders for brightness/contrast)
Extend to video processing

📌 Author
Arpit Bangre

