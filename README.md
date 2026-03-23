# cancertracker
Cancer Threat Tracker: A Python bioinformatics tool assessing risk via weighted biomarkers. Integrates physical symptoms, genetic mutations (BRCA1/TP53), and oncogene activity (HER2). Features an interactive risk engine using dictionaries, loops, and conditional logic to categorize data into Low, Moderate, or High threat levels.
🛠️ Features
Weighted Risk Database: Uses a dictionary to assign specific "risk points" to various biomarkers (e.g., brca1_mutation carries more weight than fatigue).

Interactive Input: A dynamic loop that asks the user to confirm the presence of specific symptoms or known genetic variants.

Risk Engine: A dedicated function that calculates the total score based on biological significance.

Instant Verdict: Provides an immediate status report based on the calculated threat score.

🧪 Biological Markers Included
The program tracks three main categories of data:

Physical Symptoms: Lumps, persistent cough, unexplained weight loss, etc.

Genetic Mutations: Key tumor suppressors and markers like TP53 and BRCA1.

Oncogene Expression: Activity levels of genes like HER2 and MYC.

💻 Technical Skills Shown
Language: Python 3

Data Structures: Dictionaries (HashMaps), Lists

Control Flow: For-loops, If-Else statements

User Interaction: Standard I/O (input/output)

⚠️ Medical Disclaimer
This program is for educational and project-building purposes only. It is NOT a medical diagnostic tool. The scores provided are based on hypothetical weights and should not be used to make actual health decisions. Always consult a medical professional for health concerns.
