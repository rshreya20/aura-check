Aura-Check 🧘‍♀️🧠
Aura-Check is a simple yet powerful stress analyzer tool based on the DASS (Depression Anxiety Stress Scales) test. It helps users assess their mental health by analyzing their responses and classifying their stress, anxiety, and depression levels.

📋 What is DASS?
The DASS is a psychological assessment instrument designed to measure the emotional states of:

Depression
Anxiety
Stress
Aura-Check digitizes this test and provides instant feedback and classification based on scientifically backed scoring.

🌟 Features
✅ Implements the standardized DASS-21 assessment
📊 Scores and classifies mental health status into normal, mild, moderate, severe, or extremely severe
🧠 Identifies levels for each component: depression, anxiety, and stress
📁 Lightweight, minimal dependencies, and easy to run
🛠️ Getting Started
Prerequisites
Python 3.7+
Jupyter Notebook (optional, for using mai.ipynb)
Required libraries listed in requirements.txt
Installation
git clone https://github.com/Nevary-Codes/aura-check.git
cd aura-check
pip install -r requirements.txt
Running the Notebook
For an interactive experience with charts, visuals, and inputs:

jupyter notebook mai.ipynb
You’ll be prompted to enter DASS-21 responses, and the tool will output categorized results.

🧪 Example Output
DASS Score:
  Depression: 16 (Moderate)
  Anxiety: 8 (Mild)
  Stress: 20 (Severe)

Suggestion: Consider speaking with a mental health professional if symptoms persist.
📂 Project Structure
aura-check/
├── mai.py             # Main script to run the DASS analyzer
├── mai.ipynb          # Jupyter Notebook version for exploration
├── requirements.txt   # Required libraries
└── README.md          # Project documentation
