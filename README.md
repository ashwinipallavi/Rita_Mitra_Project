
# 🌾 Raita Mitra – Smart Agriculture System using Machine Learning

Raita Mitra is a machine learning–based decision support system designed to help farmers make informed agricultural decisions. The system provides crop recommendations, fertilizer suggestions, and plant disease detection using data-driven and image-based models.

---

## 📌 Project Description

Agriculture faces major challenges due to uncertainty in crop selection, improper fertilizer usage, and delayed disease detection. Traditional methods rely heavily on experience and generalized advice, often leading to suboptimal outcomes.

Raita Mitra addresses these challenges by integrating Machine Learning (ML) and Deep Learning (DL) techniques to provide personalized and accurate recommendations based on soil parameters, weather conditions, crop data, and plant leaf images.

---

## 🎯 Objectives

- Provide personalized crop recommendations based on soil and environmental parameters  
- Suggest suitable fertilizers to improve yield and reduce wastage  
- Detect and classify plant diseases using leaf images  
- Improve agricultural productivity while promoting sustainability  
- Reduce dependency on traditional and manual advisory systems  

---

## 🚜 Features

- 🌱 Crop Recommendation System  
- 🧪 Fertilizer Recommendation System  
- 🌿 Plant Disease Detection  
- 📊 High accuracy using Random Forest and ResNet models  
- 🖥️ User-friendly web interface (Flask-based)

---

## 🧠 Technologies Used

### Programming & Tools
- Python 3.7.4  
- Jupyter Notebook  
- Flask  
- Git & GitHub  

### Libraries
- NumPy  
- Pandas  
- Scikit-learn  
- PyTorch  
- Matplotlib  

---

## 🧩 Machine Learning Models

| Module | Algorithm |
|------|----------|
| Crop Recommendation | Random Forest |
| Fertilizer Recommendation | Random Forest |
| Plant Disease Detection | ResNet-9 (CNN), Naive Bayes |

---

## 📊 Dataset Details

- PlantVillage Dataset (Augmented)  
- ~87,000 RGB images  
- 38 classes (14 plants, 26 diseases)  
- 80/20 Train–Validation split  

---

## ⚙️ Installation & Execution

```bash
git clone https://github.com/ashwinipallavi/Rita_Mitra_Project.git
cd Rita_Mitra_Project
pip install -r requirements.txt
python app.py
```

Access in browser:
```
http://localhost:5000
```

---

## 🧪 Testing & Validation

- Functional testing for all modules  
- Input validation  
- Image-based disease testing  

---

## 📈 Results

| Algorithm | Accuracy |
|---------|----------|
| Random Forest | 99% |
| Naive Bayes | 99% |
| SVM | 97% |
| Logistic Regression | 95% |
| XGBoost | 99.3% |

---

## 🔮 Future Enhancements

- Real-time disease detection  
- Multilingual support  
- Weather API integration  
- Mobile application  

---

## 👩‍💻 Author

Pallavi  
BE – Computer Science Engineering  
The National Institute of Engineering, Mysuru  

---

## 📜 License

GNU General Public License v3.0 (GPL-3.0)
