# ⚙️ Alloy Tensile Strength Predictor (Materials Informatics)

A machine learning regression model designed to predict the Ultimate Tensile Strength (UTS) of steel alloys based on their chemical composition and heat treatment parameters.

## 🚀 The Concept: Materials Informatics
Traditional materials discovery and mechanical testing (e.g., tensile testing) is a time-consuming and expensive laboratory process. This project explores the field of **Computational Materials Science**, leveraging data-driven algorithms to accelerate alloy design and predict mechanical properties before a physical prototype is even cast.

## 🔬 Features & Parameters
The Random Forest model evaluates the following metallurgical parameters to output an estimated strength in Megapascals (MPa):
- **Carbon (%)**: Primary hardening element.
- **Manganese (%)**: Increases hardenability and tensile strength.
- **Silicon (%)**: Deoxidizer that strengthens ferrite.
- **Quenching Temperature (°C)**: Austenitizing temperature prior to rapid cooling.

## 🛠️ Tech Stack
- **Python 3**
- **Scikit-Learn** (Random Forest Regressor)
- **Pandas & NumPy** (Data Generation & Preprocessing)

## 💡 Engineering Impact
By predicting material behavior computationally, engineers can optimize chemical compositions to reach target mechanical properties, significantly reducing R&D costs and time-to-market in manufacturing and metallurgy.
