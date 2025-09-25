# 🎨 Cartoonify Image using Python & OpenCV

This project takes a **real photo** and converts it into a **cartoon-style image** using Digital Image Processing (DIP) techniques.  
It’s a fun and creative way to learn **image filtering, edge detection, and color processing** with OpenCV.  

---

## 📌 Project Steps
Here’s the step-by-step process I implemented:

1️⃣ **Read the Image**  
   - Load the input photo using OpenCV.  

2️⃣ **Convert to Grayscale**  
   - Turn the image into black & white for further processing.  

3️⃣ **Remove Noise (Median Blur)**  
   - Smooth the image while keeping edges sharp.  

4️⃣ **Detect Edges (Adaptive Thresholding)**  
   - Extract the sketch-like outlines of the photo.  

5️⃣ **Color Smoothing (Bilateral Filter)**  
   - Reduce the number of colors for a cartoon effect while preserving edges.  

6️⃣ **Combine Edges + Colors**  
   - Overlay the detected edges on the smoothed image → Final Cartoon!  

---

## 🛠️ Tools & Technologies
- **Python** 🐍  
- **OpenCV** – for image processing  
- **NumPy** – for array operations  
- **Matplotlib** – for displaying results  

---

## 🖼️ Output Example

| Original Image | Edges Detected | Cartoonified Image |
|----------------|----------------|--------------------|
| ![original](example/original.jpg) | ![edges](example/edges.jpg) | ![cartoon](example/cartoon.jpg) |

---

## 🚀 How to Run

### Option 1: Google Colab (Easy)
1. Open [Google Colab](https://colab.research.google.com/)  
2. Upload your photo (e.g., `flower.jpg`)  
3. Copy-paste the notebook code  
4. Run → Enjoy your cartoonified image 🎉  

### Option 2: Local Machine
```bash
pip install opencv-python numpy matplotlib
