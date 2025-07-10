# 🥗 NutriTrack – Personalized Nutrition Recommendation System

NutriTrack is a machine learning-powered food recommendation platform designed to offer **personalized nutrition guidance**. By combining FastAPI, Streamlit, and intelligent recommendation algorithms, NutriTrack helps users achieve their health goals through tailored dietary suggestions based on their preferences, dietary restrictions, and nutritional needs.

---

## 📁 Project Structure

NutriTrack/
├── Assets/ → Design files, images, branding assets
├── Data/ → Dataset files and processed nutrition data
├── Docs/ → Project documentation (PDFs, Report, References)
├── FastAPI_Backend/ → Python backend with ML model & API endpoints
├── Streamlit_Frontend/ → Interactive frontend UI for user interaction
├── .gitignore → Git ignore file
├── CODE_OF_CONDUCT.md → Contributor guidelines and behavior standards
├── docker-compose.yml → Docker configuration for app deployment
├── food-recommendation-system.ipynb → Core ML logic and experiments
├── LICENSE → Open-source license (MIT/Apache, etc.)
├── README.md → This file


---

## 🚀 Features

- 🔍 **Personalized Recommendations** based on user profiles
- 🧠 **ML-powered Engine** using KNN and cosine similarity
- 🧾 **Nutrition Database Integration** for accurate food data
- 🌐 **FastAPI** backend for fast, scalable API serving
- 💻 **Streamlit** frontend for interactive user input and results
- 🐳 **Dockerized Deployment** for easy installation and scaling

---

## 🛠️ Technologies Used

| Component       | Technology              |
|----------------|--------------------------|
| Frontend        | Streamlit, Bootstrap     |
| Backend         | FastAPI, Flask (API)     |
| ML/Analysis     | scikit-learn, Pandas, NumPy |
| Visualization   | Matplotlib, Seaborn      |
| Deployment      | Docker, docker-compose   |
| Database/API    | Nutrition DB APIs        |

---

## 🧠 How It Works

1. **User Input**: User enters personal info (age, weight, activity level, etc.)
2. **Profile Analysis**: Backend processes inputs and calculates nutrient needs
3. **Recipe Filtering**: ML model filters recipes using cosine similarity
4. **Recommendations**: User gets tailored food suggestions via frontend
5. **Feedback Loop**: User interactions help refine future predictions


