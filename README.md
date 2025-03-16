# synapse_2.0_neuro_nexus
Allergen Detection System
# 🍽️ Allergen Detection & Dietary Assistance System  

🏆 ML-Based Food Safety & Calorie Management Solution  

📌 Overview  
This project is an **AI-powered food safety assistant** that helps users identify allergens in food, suggests safer alternatives, provides calorie insights, and recommends allergy specialists. The system is built using **Machine Learning (XGBoost, TF-IDF)** and an **interactive Gradio UI** for accessibility.  

## 🚀 Features  
✅  Allergen Detection – Identifies if a dish contains a specific allergen.  
✅  Alternative Ingredients– Suggests safer substitutes for allergenic ingredients.  
✅  Safe Dish Recommendations – Provides a list of dishes without the selected allergen.  
✅  Calorie Management – Checks if a dish fits within a user’s calorie limit and suggests alternatives.  
✅  Allergy Specialists – Displays a list of expert doctors specializing in food allergies.  
✅  AI Model Integration– Uses **XGBoost & TF-IDF** for accurate allergen detection.  
✅  User-Friendly UI – Multi-page **Gradio** web app with dropdown selections.  

---

## ⚙️ Tech Stack  
- Machine Learning: XGBoost, TF-IDF, Scikit-learn  
- Dataset: Custom-built dataset of **200+ Indian dishes** with ingredients, allergens & calories  
- Frontend: Gradio (for UI)  
- Backend: Python, Pandas, NumPy  
- Deployment: Google Colab  

---

## 📂 Dataset Structure  
The dataset contains **200+ Indian dishes** with the following fields:  

| Column Name            | Description                                      |
|------------------------|--------------------------------------------------|
| Food Item          | Name of the dish                                |
| Ingredients       | List of ingredients used in the dish            |
| Allergens          | Common allergens present (if any)               |
| Alternative Ingredients| Suggested non-allergenic substitutes        |
| Calories         | Caloric content of the dish                     |

---

## 📊 Machine Learning Model  
1️⃣ Data Processing  
- TF-IDF Vectorization for feature extraction from text-based Ingredients.  
- Target variable: Allergen Presence (1 = Yes, 0 = No).  

2️⃣ Model Training  
- XGBoost Classifier trained with an 80-20 train-test split.  
- Evaluated using accuracy score.  
- Final Accuracy: `~XX%` *(To be updated after training)*.  

![image](https://github.com/user-attachments/assets/794743db-f677-4ea2-b6c5-c919ca4f8311)
![image](https://github.com/user-attachments/assets/d19952e2-7701-4456-a328-579eee9dd02d)
![image](https://github.com/user-attachments/assets/7d66967c-c2d2-43e3-ba56-d59a4515acaa)





