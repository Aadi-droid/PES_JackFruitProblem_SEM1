# PES_JackFruitProblem_SEM1
A Python-based command-line healthcare application that performs age group analysis, symptom-based illness checking, BMI calculation, and appointment token generation using CSV data.

<body>
  <p>🏥 Healthcare Management & Symptom Analysis System (Python)<br></p>
  <p>
    This project is a Python-based command-line healthcare application developed as an academic mini project. It combines patient data analysis, basic illness symptom checking,       BMI calculation, and appointment token generation into a single integrated program.
    The application is designed to demonstrate the use of Python programming, CSV file handling, conditional logic, and data analysis using Pandas in a healthcare-related context. 
  </p>
  🔹 Features
    📊 Age Group Analysis
  
  Reads patient data from a CSV file (fake_patient.csv)
  
  Categorizes patients into predefined age groups:
  
  Child, Teen, Young Adult, Middle Age, Senior
  
  Displays:
  
  Age group distribution
  
  Percentage of patients in each group
  
  🧾 Appointment Token Generator
  
  Accepts number of patients and their names
  
  Automatically assigns sequential appointment tokens
  
  Saves the token list to a CSV file (AppointmentTokens.csv)
  
  Useful for managing patient queues
  
  🩺 General Illness Symptom Checker
  
  Interactive symptom-based checker using user input
  
  Asks questions related to:
  
  Fever, cough, cold
  
  Gastric symptoms
  
  Dengue-like symptoms
  
  Dehydration indicators
  
  Emergency red flags
  
  Uses rule-based logic to identify the closest matching illness
  
  Provides general health advice
  
  Includes a clear medical disclaimer
  
  ⚠ This tool is for educational purposes only and is not a replacement for professional medical diagnosis.
  
  ⚖ BMI (Body Mass Index) Calculator
  
  Calculates BMI using user height and weight
  
  Supports unit conversion:
  
  kg ↔ lbs
  
  cm ↔ meters
  
  Categorizes BMI into:
  
  Underweight
  
  Normal weight
  
  Overweight
  
  Obese
  
  Displays:
  
  BMI value
  
  BMI category (with colored terminal output)
  
  Ideal weight range
  
  Personalized lifestyle suggestions
  
  🔹 Technologies Used
  
  Python
  
  Pandas – CSV file handling and data analysis
  
  Command Line Interface (CLI)
  
  CSV files – Data input and output
  
  🔹 Project Highlights
  
  Modular structure with reusable functions
  
  Demonstrates real-world healthcare use cases
  
  Uses conditional logic to simulate medical decision-making
  
  Includes data storage and retrieval using CSV files
  
  Terminal-based UI with colored output for better readability
  
  ⚠ Disclaimer
  
  This project is intended only for educational purposes.
  It does not provide medical diagnosis and should not be used for real medical decisions.
  Always consult a qualified healthcare professional for medical concerns.
  
  🚀 How to Run the Project
  
  Install required dependency:
  
  pip install pandas
  
  
  Ensure fake_patient.csv is present in the same directory
  
  Run the program:
  
  python app.py
  
  👥 Team Project
  
  This project was developed collaboratively as part of an academic mini project to demonstrate Python programming concepts and basic healthcare data analysis.
