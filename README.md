🧬 Cancer Threat Tracker (PORT)
📌 Project Overview
The Personalized Oncogenic Threat Tracker (PORT) is a Python-based diagnostic simulation. It evaluates potential health risks by weighing physical symptoms against high-priority genetic markers and oncogene expression levels.

This project demonstrates the use of Python dictionaries, modular functions, and interactive loops to transform qualitative patient data into a quantitative risk score.

🚀 How to Set Up
Since this is a lightweight Python script, there are no complex dependencies or external libraries to install.

Install Python: Ensure you have Python 3.x installed on your machine. You can download it from python.org.

Download the Script: Download the cancertracker.py file from this repository.

Open an Editor: Open the file using IDLE (included with Python) or any code editor like VS Code or PyCharm.

💻 How to Use
Run the Program: In IDLE, open cancertracker.py and press F5, or run the command python cancertracker.py in your terminal/command prompt.

Input Symptoms: The program will prompt you with a series of questions regarding symptoms (e.g., "lump") and genetic markers (e.g., "tp53_mutation").

Answer Prompts: Type yes or no for each prompt and press Enter.

View Results: After the final question, the engine will calculate your score and display a Risk Status:

High Threat (70+): Significant red flags detected.

Moderate Risk (30-69): Multiple indicators present.

Low Risk (<30): Minimal markers found.

📂 Project Structure
cancertracker.py: The main Python script containing the logic and database.

README.md: Project documentation and setup instructions.

🧬 Scoring Logic
The program uses a weighted dictionary to prioritize findings:

Genetic Mutations (BRCA1, TP53): 45-50 points (High priority).

Physical Symptoms (Lump, Weight Loss): 25-40 points (Medium priority).

General Symptoms (Fatigue, Night Sweats): 5-10 points (Low priority).

⚠️ Medical Disclaimer
This project is for educational and programming demonstration purposes only. It is not a medical tool and should not be used for actual health diagnosis. Always consult a medical professional for health concerns.
