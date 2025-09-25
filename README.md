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

<img width="619" height="203" alt="image" src="https://github.com/user-attachments/assets/4bb51c80-8152-44ba-a093-2853fdf9752f" />


---
## 🌟 Future Ideas

- 🎥 **Real-time cartoonify with webcam feed**  
  Capture live video from webcam and apply cartoon effect in real-time.  

- 🎨 **Add creative filters (Pencil Sketch / Comic Strip)**  
  Extend the project with extra artistic filters for more fun.  

- 📱 **Deploy as a mobile or web app**  
  Make the project interactive by turning it into a simple app for users.  

