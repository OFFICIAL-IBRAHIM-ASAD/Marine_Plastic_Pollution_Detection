# 🌊 AQUA-VISION AI 

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)
![Streamlit](https://img.shields.io/badge/Streamlit-GUI-red)

An AI-powered image classification system designed to identify plastic pollution in marine and freshwater environments. This project leverages Deep Learning to provide an accessible tool for environmental monitoring and awareness.

## 📌 Project Overview
Plastic pollution is one of the greatest threats to our ecosystems. This project uses a **Convolutional Neural Network (CNN)** to analyze images of water bodies and classify them as containing plastic or being clean. To make this technology accessible to non-technical users, I developed an interactive **Streamlit GUI** for real-time image analysis.

**Supervised by:** Ma'am Noreen Khalid

---

## 🚀 Features
* **Deep Learning Engine:** Built using TensorFlow/Keras with customized layers for feature extraction.
* **Smart Data Pipeline:** Automatically processes images and labels via CSV mapping.
* **Interactive GUI:** User-friendly interface for image uploads and instant classification.
* **Data Augmentation:** Robust training using rotation, zooming, and flipping to ensure high generalization.

---

## 🛠️ Tech Stack
* **Language:** Python
* **Deep Learning:** TensorFlow, Keras
* **Data Handling:** Pandas, NumPy
* **GUI Framework:** Streamlit
* **Image Processing:** PIL (Pillow)
* **Visualization:** Matplotlib

---

## 📂 Project Structure
```text
Plastic_Detector/
├── app.py                     # Streamlit GUI Application
├── plastic_detection_model.keras # Trained CNN Model
├── requirements.txt           # List of dependencies
├── Marine_Dataset/            # Dataset directory
│   ├── train/                 # Training images & _classes.csv
│   ├── valid/                 # Validation images & _classes.csv
│   └── test/                  # Test images & _classes.csv
└── README.md                  # Project documentation

```

---

## ⚙️ Installation & Setup

1. **Clone the repository:**
```bash
git clone [https://github.com/your-username/plastic-detection.git](https://github.com/your-username/plastic-detection.git)
cd plastic-detection

```


2. **Create a Virtual Environment:**
```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

```


3. **Install Dependencies:**
```bash
pip install -r requirements.txt

```


4. **Run the Application:**
```bash
streamlit run app.py

```



---

## 📊 Model Performance

* **Architecture:** Sequential CNN (Conv2D, MaxPooling, Dropout, Dense).
* **Input Size:** 150x150 pixels.
* **Loss Function:** Binary Crossentropy.
* **Optimizer:** RMSprop (Learning Rate: 1e-4).

---

## 💡 Challenges Overcome

* **Data Structure:** Successfully pivoted from folder-based classification to a robust CSV-based image mapping logic.
* **Performance Tuning:** Overcame initial accuracy hurdles by implementing data augmentation and exploring transfer learning strategies.
* **GUI Integration:** Bridged the gap between a complex backend model and a simple, intuitive user interface.

---

## 🤝 Contributing

Contributions are welcome! If you'd like to improve the model accuracy or add new features:

1. Fork the project.
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

---

## 📜 License

This project is licensed under the MIT License - see the LICENSE file for details.
