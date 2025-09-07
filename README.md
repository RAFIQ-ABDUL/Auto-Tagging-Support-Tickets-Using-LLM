# 🏷️ Auto Tagging Support Tickets Using LLM

This project demonstrates how to use a **Large Language Model (LLM)** to automatically tag and categorize support tickets. The system helps customer service teams by reducing manual effort, improving response time, and ensuring consistent categorization.

---

## 🚀 Project Overview

1. **Problem Statement**
   - Customer support receives thousands of tickets daily.
   - Manual tagging is time-consuming, error-prone, and inconsistent.
   - Goal: Automate ticket classification using LLMs.

2. **Solution**
   - Used an **LLM** to analyze ticket text and assign relevant tags.
   - Tags include categories like *billing, technical issue, account, refund, feature request*, etc.
   - Built a pipeline for **preprocessing, inference, and tagging**.

---

## 🛠️ Tech Stack

- **Languages:** Python  
- **Libraries/Frameworks:**  
  - Hugging Face Transformers / OpenAI API (LLM for tagging)  
  - Pandas, NumPy (data handling)  
  - Scikit-learn (preprocessing pipeline)  
  - Matplotlib / Seaborn (EDA & visualization)  

---

## 📊 Workflow

1. **Data Preparation**
   - Collected support ticket dataset (text + manual tags).  
   - Cleaned text (lowercasing, removing special characters, etc.).  

2. **Exploratory Data Analysis (EDA)**
   - Visualized ticket distribution across categories.  
   - Identified most frequent tags and imbalances.  

3. **LLM Integration**
   - Prompted the LLM with support ticket text.  
   - Generated most probable tag(s) with confidence.  

4. **Pipeline**
   - Preprocessing → LLM inference → Post-processing → Tag assignment.  

---

## ⚙️ Installation & Usage

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/auto-tagging-llm.git
   cd auto-tagging-llm
