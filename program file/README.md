# Smart Fruit Sorting System 🍎🍌

This project uses **Transfer Learning** with **MobileNetV2** to classify fruit images as **Fresh** or **Rotten**.  
The application is built using **Flask** and provides a web interface for users to upload an image and receive a classification result.

---

## 🔧 Requirements

Install the necessary Python libraries using:

```bash
pip install -r requirements.txt
```
dataset link:https://www.kaggle.com/datasets/muhriddinmuxiddinov/fruits-and-vegetables-dataset

---

## 📁 Project Structure

```
SmartFruitSorting/
│
├── model_building.py         # Model training and saving script
├── app.py                    # Flask web app
├── requirements.txt          # Python dependencies
├── README.md                 # Project description
└── templates/
    └── index.html            # Frontend interface
```

---

## 🚀 How to Run

### 1. Train the model
Place your dataset in `dataset/train` and `dataset/val`, then run:
```bash
python model_building.py
```

### 2. Start the web application
Make sure `fruit_model.h5` is in the same folder as `app.py`. Then run:
```bash
python app.py
```

Visit [http://127.0.0.1:5000](http://127.0.0.1:5000) in your browser.

---

## 📷 Prediction Output

- Upload an image of a fruit.
- The app classifies it as **Fresh** or **Rotten**.

---

## ✨ Author
Mallika 🌸  
Intern @ SmartBridge  
