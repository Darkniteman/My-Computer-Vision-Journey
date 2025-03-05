## 📌 Project Overview  
This project demonstrates how to remove a blue screen background from a video using OpenCV in Python.  
By defining a specific blue color range, we can replace the background with a different image or video.  

## 🛠️ Technologies Used  
- Python  
- OpenCV (`cv2`)  
- NumPy  

## 🔍 Understanding the Concept  
In this project, we detect the blue background by setting **lower and upper color boundaries** and use `cv2.inRange()` to create a mask. The mask is then applied to remove the background and replace it with another image.  

### **🔹 Why Do We Use Lower and Upper Boundaries?**  
- **Lower Bound (`lower_blue`)**: This defines the darkest blue shade we want to detect.  
- **Upper Bound (`upper_blue`)**: This defines the lightest blue shade to include in detection.  
