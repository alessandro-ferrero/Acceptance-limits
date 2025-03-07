# Acceptance and Rejection Limits Calculation

This program computes **acceptance** (`Acceptance limits.ipynb`) and **rejection** (`Rejection limits.ipynb`) limits based on the **ISO-IEC Guide 98-4** and **JCGM 106:2012** recommendations.

It is designed to support the research paper:

## *Risk-aware decisions: considering admissible risk and measurement uncertainty in setting acceptance limits*  

### 📚 Authors:  
- **Alessandro Ferrero**  
- **Harsha Vardhana Jetti**  
- **Sina Ronaghi**  
- **Simona Salicone**  

---

## 📌 How to Use This Script  

There are two main ways to run this program:

### 1️⃣ Running Locally  

To run the script on your local machine, follow these steps:

1. **Clone the repository** using HTTPS, SSH, GitHub CLI, or download a **zipped version** from GitHub.  
2. Ensure that **Jupyter Notebook** is installed on your system.  
3. The script is developed using **Python 3.12.0**, so install Python if necessary.  
4. Install required dependencies by running:

   ```sh
   pip install -r requirements.txt
5. After setup, you can modify the following parameters as needed:

**Distribution parameters:**
- Maximum Admissible Limit (MAL)
- Monte-Carlo simulation-derived value distributions (R98.txt, R102.txt). These values are those that can be reasonably attributed to the measurand obtained from a Monte-Carlo simulation for the case of an unknown distribution.

💡For further details on parameter adjustments, refer to the research paper.

### 2️⃣ Running on Google Colab
You can also run the script directly on Google Colab without installing anything. Access the respective notebooks using the links below:

📌 Acceptance Limits Notebook: https://colab.research.google.com/drive/1bPlo2MwCUzFnrIiih2DRkTh1fosLqteu?usp=sharing

📌 Rejection Limits Notebook: https://colab.research.google.com/drive/1LLYinxhv_6cg3eSokeu43775w2VzI8UB?usp=sharing

💡 Note: Running the script on Google Colab means:
The program executes with predefined settings.
Parameters such as MAL, distribution parameters, and Monte-Carlo simulated values (R98.txt, R102.txt) cannot be modified.
For more details, please refer to the research paper.
