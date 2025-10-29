# 🎨 Color Recognition using Python

This project identifies the name of a color in an image when a user clicks on it.  
It uses **OpenCV** and **Pandas** to read an image, capture mouse events, and map RGB values to color names.

---

## 🧠 Overview
The goal of this project is to detect and display the closest color name from a predefined dataset based on the pixel RGB value.

When the user clicks anywhere on the image window:
- The program retrieves the RGB value of that pixel.
- It finds the nearest color name from a color dataset (CSV file).
- The color name and RGB values are displayed on the image.

---

## ⚙️ Features
- Detects color name on mouse click  
- Displays RGB values in real-time  
- Works with any image file (JPG, PNG, etc.)  
- Easy to extend with custom color datasets  

---

## 🧩 Technologies Used
- **Python 3**
- **OpenCV** – image handling and GUI interaction  
- **Pandas** – CSV color data processing  
- **NumPy** – numerical operations  

---

## 📁 Project Structure
color-recognition/
│
├── color_detection.py # Main Python script
├── colors.csv # Color dataset (name, R, G, B)
├── colorpic.jpg # Example input image
└── README.md # Project documentation

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/ShivamRathod0110/Python-Projects.git
   cd Python-Projects/color-recognition

2.Install dependencies
```bash
pip install opencv-python pandas numpy

3.Run the program
```bash
python color_detection.py

Click on the image window
The color name and RGB values will appear instantly.

Example Output
When you click on any region of the image, you’ll see something like this:
Color: Sky Blue | RGB(135, 206, 235)
