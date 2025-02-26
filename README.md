# HealthCare ChatBot

## Overview
This project implements a **HealthCare ChatBot** that predicts possible diseases based on user-reported symptoms. It utilizes **machine learning models (Decision Tree, SVM)** to classify symptoms and suggest potential conditions, along with precautions and severity analysis. The bot interacts with users via text-based input and includes **text-to-speech functionality**.

## Features
- **Symptom-Based Disease Prediction**: Uses a Decision Tree classifier to identify possible conditions.  
- **Machine Learning Models**: Supports **Decision Tree & SVM** for improved classification.  
- **Severity & Precaution Suggestions**: Recommends steps based on symptom severity.  
- **Text-to-Speech Support**: Reads out disease predictions and suggestions.  
- **Pattern Matching**: Helps in recognizing symptoms from user input.  

## Technologies Used
- **Python** (Core logic & chatbot functionality)  
- **Scikit-Learn** (Machine Learning models)  
- **Pandas** (Data handling)  
- **Numpy** (Numerical operations)  
- **Pyttsx3** (Text-to-Speech)  
- **Regex** (Pattern matching for symptoms)  

## Setup Instructions
1. **Install Dependencies**:  
   ```bash
   pip install pandas numpy scikit-learn pyttsx3
   ```
   
2. Ensure Data Availability:
- Place **Training.csv** and **Testing.csv** in a Data/ folder.
- Place **symptom_Description.csv**, **symptom_severity.csv*, and **symptom_precaution.csv** in a MasterData/ folder.

3. Run the ChatBot:
```bash
python chat_bot.py
```

## Usage
1. Enter your symptoms when prompted.
2. The bot will predict possible diseases.
3. It provides precautions, severity analysis, and treatment suggestions.
4. Users receive text-to-speech output for assistance.

##Future Enhancements
- Integrate Deep Learning models for better predictions.
- Add voice-based interaction.
- Deploy as a web-based chatbot.
