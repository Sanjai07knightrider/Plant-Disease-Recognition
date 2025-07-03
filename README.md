# 🌿 Plant-Disease-Recognition

This project is a **deep learning-based image classification system** that detects plant leaf diseases. It utilizes a **Convolutional Neural Network (CNN)** trained on the **PlantVillage dataset** and is deployed through a lightweight **Flask web app** that works **offline**.

> 💡 Farmers can upload an image of a plant leaf and receive instant feedback on the disease condition — no internet required after setup!

---

## 🎯 Objectives

- ✅ Identify 39 different classes of healthy and diseased plant leaves
- ✅ Provide a web interface for uploading leaf images
- ✅ Enable **offline usage** for rural and underconnected regions
- ✅ Achieve high classification accuracy (~97%)
- ✅ Make the system scalable and easy to update

---

## 🚀 Features

- 🧠 **CNN-based model** trained using TensorFlow + Keras
- 🖼️ Simple web interface built with **Flask**
- 🔌 Works without an internet connection after setup
- ⚡ Real-time predictions in under 2 seconds
- 🧪 Tested with high accuracy and performance
- 🛠️ Easy to extend with new plant species and diseases

---

## 📁 Project Structure

```
Plant-Disease-Recognition/
├── app.py                         # Main Flask server
├── model/
│   └── plant_disease_model.keras # Trained CNN model
├── plant_disease.json            # Index-to-label mapper
├── requirements.txt              # Python dependencies
├── static/
│   └── uploadimages/             # Uploaded images
├── templates/
│   └── home.html                 # Web UI template
└── README.md
```

---

## 🛠 Setup Instructions

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/Plant-Disease-Recognition.git
cd Plant-Disease-Recognition
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Application

```bash
python app.py
```

Then go to [http://localhost:5000](http://localhost:5000) in your browser.

---

## 🧠 Model Details

- **Architecture**: Custom CNN with Conv2D, MaxPooling, Dropout
- **Framework**: TensorFlow & Keras
- **Dataset**: [PlantVillage](https://www.kaggle.com/datasets/emmarex/plantdisease)
- **Image Size**: 160x160 pixels
- **Accuracy**: ~97% on validation set
- **Classes**: Tomato, Apple, Potato, Corn, Grape, etc.

---

## 🧪 Performance Summary

| Metric             | Value            |
|--------------------|------------------|
| Validation Accuracy| ~97%             |
| Prediction Time    | ~1.5–2 seconds   |
| Model Size         | ~20 MB           |
| RAM Usage          | <500 MB          |

---

## 📷 Example Use Case

1. A farmer uploads a leaf image (e.g., tomato leaf).
2. The model detects **"Tomato___Leaf_Mold"**.
3. Result is shown on the same page within 2 seconds.

---

## 🧩 Future Enhancements

- 📱 Convert to Android/iOS app
- 🎥 Add live camera feed support
- 🔍 Integrate Grad-CAM for explainability
- 🈳 Translate UI into regional languages (Tamil, Hindi, etc.)
- ☁️ Optional cloud deployment (Heroku, AWS)

---

## 🤝 Contributing

Contributions are welcome!

```bash
1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Open a Pull Request
```

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 📬 Need Help?

Feel free to open an issue or contact me via email.  
Together, we can grow smarter farming with AI! 🌾
