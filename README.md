# Cosmetic_Ingredient_Risk_Indicator

# AI-Based Ingredient Risk Indicator

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Methodology](#methodology)
- [Results](#results)
- [Future Enhancements](#future-enhancements)
- [Contributors](#contributors)
- [License](#license)

## Introduction
The **AI-Based Ingredient Risk Indicator** is an advanced AI-driven tool designed to evaluate the safety of cosmetic ingredients. Users can upload an image of a product's ingredient list, which is then processed using **Optical Character Recognition (OCR)** to extract text. The extracted ingredients are analyzed against a comprehensive database to classify them as **"Safe," "Caution," or "Harmful."**

This project aims to provide consumers with **transparent, reliable** information regarding cosmetic ingredients, helping them make safer and informed choices.

## Features
✅ **OCR-Based Text Extraction:** Extracts ingredients from product labels.
✅ **AI-Powered Analysis:** Uses NLP and machine learning to assess ingredient risks.
✅ **Ingredient Classification:** Categorizes ingredients as **safe, cautionary, or harmful**.
✅ **User-Friendly Web Interface:** Simple UI for uploading images and viewing results.
✅ **Feedback Mechanism:** Users can submit corrections to improve the AI model.
✅ **Scalability:** Potential applications in other industries like food safety and pharmaceuticals.

## Technology Stack
- **Programming Language:** Python
- **Machine Learning & NLP:** TensorFlow, Scikit-learn, SentenceTransformer
- **OCR:** Tesseract OCR
- **Web Framework:** Flask/Django
- **Database:** SQLite/MySQL
- **Frontend:** HTML, CSS, JavaScript (React/Bootstrap)

## Installation
To set up the project locally, follow these steps:

### Prerequisites
Ensure you have the following installed:
- Python 3.8+
- pip (Python package manager)
- Tesseract OCR

### Steps
```bash
# Clone the repository
git clone https://github.com/yourusername/ingredient-risk-indicator.git
cd ingredient-risk-indicator

# Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

# Install required dependencies
pip install -r requirements.txt

# Run the application
python app.py
```

## Usage
1. Open the web application in your browser.
2. Upload an image containing a product's ingredient list.
3. The system will process the image and extract text using OCR.
4. Ingredients will be classified as **Safe, Caution, or Harmful.**
5. View results and additional information about harmful ingredients.
6. Submit feedback if you notice any incorrect classifications.

## Project Structure
```
├── dataset/                # Predefined ingredient database
├── models/                 # Trained AI/ML models
├── static/                 # Frontend assets (CSS, JS, Images)
├── templates/              # HTML templates
├── app.py                  # Main application script
├── requirements.txt        # Python dependencies
├── README.md               # Project documentation
```

## Methodology
### 1. **Data Collection**
- Large dataset of known cosmetic ingredients.
- Mapping of ingredients to hazard categories (Safe, Caution, Harmful).

### 2. **Text Extraction**
- **Tesseract OCR** extracts text from uploaded images.
- **Preprocessing techniques** remove noise, correct misspellings.

### 3. **Ingredient Classification**
- Uses **SentenceTransformer embeddings** for matching ingredient names.
- **Cosine similarity metric** determines the closest match.
- **Decision Tree Classifier** classifies ingredients into risk categories.

### 4. **User Interface & Feedback Loop**
- Web-based application for easy user interaction.
- Feedback from users refines the AI model for better accuracy.

## Results
✔ **High Accuracy**: 85%+ accuracy in identifying harmful ingredients.
✔ **Fast Processing**: Results displayed in under 5 seconds.
✔ **User Feedback Integration**: Improves AI predictions over time.
✔ **Scalable Design**: Easily extendable to other domains (food, pharmaceuticals).

## Future Enhancements
- 📌 **Mobile App Development** for better accessibility.
- 📌 **Real-Time API** integration for instant ingredient checks.
- 📌 **Support for Multiple Languages** to expand global reach.
- 📌 **Expanded Database** with more regulatory standards.

## Contributors
- **Vemula Chetan Nihith**  
- **Abhinav Vuddagiri**  
- **Sapare Aravind**  
- **Siva Gopal Krishna**  
- **Mentor: Dr. Hirdesh Pharasi**  
