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

The cancertracker.py engine categorizes inputs into four distinct "Risk Tiers" based on Indian clinical prevalence and biological impact.

1. High-Priority Indicators (Weight: 40-50)
These are "Red Flag" markers. In the Indian context, these often provide the highest statistical correlation with oncogenic activity.

Genetic Markers: Mutations in BRCA1 or TP53 (The "Guardians of the Genome").

Localized Habits: Chronic use of Gutkha, Khaini, or Bidi (Primary drivers of oral and lung threats in South Asia).

Clinical Signs: Painless swollen lymph nodes or sudden seizures with no prior history.

2. Physical & Sensory Symptoms (Weight: 20-35)
These are observable changes in the "Chassis" (the body) that suggest a developing condition.

Visible Changes: New mole growth, skin dimpling, or persistent hoarseness.

Functional Shifts: Sudden changes in bowel habits or difficulty swallowing (Dysphagia).

Unusual Bleeding: Any unexplained internal or external bleeding.

3. Lifestyle & Environmental Risks (Weight: 10-25)
These are "Background Drivers." They increase the body's Total Toxic Load.

Environmental: Long-term exposure to Chulha smoke (indoor air pollution) or asbestos.

Dietary: High intake of charred/grilled foods and reused cooking oils (Carcinogenic HCAs).

Hereditary: A documented family history of similar conditions.

4. Psychosocial & Systemic Markers (Weight: 5-15)
These track the Systemic Stress Response. While "non-specific," they help the engine understand the body's overall state of exhaustion.

Emotional: A persistent "Sense of Impending Doom" or sudden apathy.

Metabolic: Night sweats, chronic fatigue, or unexplained weight loss.

Sleep: Chronic insomnia or waking up unrefreshed (Restorative Deficit).

⚠️ Medical Disclaimer
This project is for educational and programming demonstration purposes only. It is not a medical tool and should not be used for actual health diagnosis. Always consult a medical professional for health concerns.
