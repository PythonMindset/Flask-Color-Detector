This is a beginner-friendly **Flask web app** that detects the **dominant colors** in an uploaded image using **K-Means clustering**.  
Upload any picture and instantly get the top color HEX codes!

---

## 🚀 Features
- Upload any image (JPG/PNG/JPEG)
- Extract top **dominant colors**
- Displays **HEX color codes**
- Simple Flask frontend
- Lightweight & fast – fully local

---

## 🛠️ Tech Stack
- Python  
- Flask  
- NumPy  
- Pillow (PIL)  
- Scikit-Learn  

---

## 📂 Project Structure
project/
│── app.py
│── color_detector.py
│── static/
│ └── uploads/
└── templates/
└── index.html


---

## 📷 Screenshot
<img width="1015" height="708" alt="image" src="https://github.com/user-attachments/assets/2af97f91-ed8a-47ab-b56d-f9b40494304c" />

---

## 💡 How It Works
1. User uploads an image  
2. Flask saves it into `static/uploads/`  
3. `color_detector.py`:
   - Resizes the image  
   - Reads pixels  
   - Clusters colors using **KMeans**  
4. Returns dominant colors as HEX codes  
5. Frontend displays them nicely  

