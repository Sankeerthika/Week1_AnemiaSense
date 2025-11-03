# 🩸 AnemiaSense – Week 1 & Week 2 Submission

## 📌 Project Overview
**AnemiaSense** is a machine learning-based system designed to detect anemia by analyzing key blood parameters such as Hemoglobin, MCV, MCH, and MCHC.  
The system aims to support early diagnosis and effective management of anemia using data-driven insights.

---

## 🎯 Week 1 Objectives
In Week 1, the focus was on:
- Collecting and loading the anemia dataset (`anemia.csv`)
- Performing data cleaning and exploratory data analysis (EDA)
- Understanding relationships between parameters and anemia results
- Preparing data for model building in Week 2

---

## 🧠 Dataset Details
| Feature | Description |
|----------|--------------|
| **Gender** | 1 = Male, 0 = Female |
| **Hemoglobin** | Hemoglobin level (g/dL) |
| **MCH** | Mean Corpuscular Hemoglobin |
| **MCHC** | Mean Corpuscular Hemoglobin Concentration |
| **MCV** | Mean Corpuscular Volume |
| **Result** | 1 = Anemic, 0 = Not Anemic |

---

## 📊 Week 1 Work Completed
- Loaded dataset from Google Drive into Colab  
- Checked for missing values and data types  
- Generated summary statistics  
- Created visualizations:  
  - Distribution of Hemoglobin levels  
  - Class distribution of anemia results  
  - Correlation heatmap of features  

---

## 🚀 Week 2 – Model Building & Evaluation

### ✅ Objectives
- Train multiple machine learning models for anemia prediction  
- Compare their accuracy and evaluate performance  
- Save the best model for deployment (Week 3)

### ⚙️ Work Completed
- Trained two models: **Logistic Regression** and **Random Forest**
- Achieved **98.95 % accuracy** with Logistic Regression  
- Achieved **100 % accuracy** with Random Forest ✅  
- Selected **Random Forest** as the best-performing model
- Saved the trained model as `model.pkl` for deployment  

### 📈 Visuals Created
- Confusion matrix for Random Forest  
- Model comparison bar chart  

---

## 💾 Files in Repository
| File Name | Description |
|------------|--------------|
| `anemia.csv` | Dataset used for training and testing |
| `Week1_AnemiaSense.ipynb` | Data preparation and EDA notebook |
| `Week2_AnemiaSense.ipynb` | Model training and evaluation notebook |
| `model.pkl` | Saved Random Forest model |
| `README.md` | Project documentation |

---

## 🧩 Next Steps (Week 3)
- Build a web interface using **Streamlit** or **Flask**  
- Integrate `model.pkl` for real-time predictions  
- Deploy the app for end-user access  

---

## 👩‍💻 Author
**Sankeerthika Paka**  
B.Tech CSE Student  

---



