# **CS3_AndreChuabio – Sentiment Analysis of Star Wars Original Trilogy**  

📌 This repository contains all relevant materials for **Case Study 3**, which involves **Natural Language Processing (NLP) sentiment analysis** on the **Star Wars Original Trilogy** dialogues. The objective is to analyze sentiment trends and evaluate how character dialogues reflect emotional shifts, with a focus on the **Skywalker family**. These findings will contribute to discussions at **Comic-Con 2025**.

---

## **📑 Table of Contents**
- [📌 Project Overview](#-project-overview)
- [📂 Dataset Information](#-dataset-information)
- [📁 Repository Structure](#-repository-structure)
- [⚡ How to Use](#-how-to-use)
- [📊 Deliverables](#-deliverables)
- [🔍 Key Insights](#-key-insights)
- [👤 Contributors](#-contributors)

---

## **📌 Project Overview**  
The growing influence of **fan engagement and nostalgia** in media has made sentiment analysis a key tool in understanding **audience perception**. **Lucasfilm** is interested in studying how **sentiment in character dialogues evolves across the Star Wars Original Trilogy**.  

This project **quantifies the emotional tone of character dialogues** using **NLP techniques**, allowing us to assess the emotional arcs of key characters, particularly the **Skywalker family**. The analysis aims to:
- 📈 **Identify sentiment trends** across Episodes IV–VI.
- 🎭 **Evaluate shifts in character emotions** based on script dialogue.
- ⚔️ **Assess the Skywalker family’s portrayal** in terms of sentiment.  

---

## **📂 Dataset Information**  
The **datasets used for this analysis** are stored in the **`DATA/`** folder and include:
- **`cleaned_dataset.csv`** – Processed dataset for sentiment analysis.
- **`star_wars_trilogy_raw.csv`** – Original dataset containing raw script dialogues.
- **`sentiment_scores.csv`** – Output sentiment scores for each line of dialogue.

The cleaned dataset was prepared by **removing noise, tokenizing text, and applying NLP preprocessing techniques**.

---

## **📁 Repository Structure**
```
📦 CS3_AndreChuabio
├── 📂 DATA
│   ├── cleaned_dataset.csv       # Processed dataset for sentiment analysis
│   ├── star_wars_trilogy_raw.csv # Original dialogue dataset
│   ├── sentiment_scores.csv      # Sentiment analysis results
│
├── 📂 Reference Materials
│   ├── sentiment_analysis_tips.pdf  # Guide for NLP-based sentiment analysis
│   ├── StarWars_Trilogy_Script.pdf  # Full trilogy script used for analysis
│
├── 📜 case_study_prompt.pdf     # Problem statement and rubric
├── 📜 deliverable_report.pdf    # Final analysis and findings
├── 📜 README.md                 # Project documentation
```

---

## **⚡ How to Use**
Follow these steps to run the sentiment analysis and explore the dataset:

### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/AndreChuabio/CS3_AndreChuabio.git
cd CS3_AndreChuabio
```

### **2️⃣ Install Dependencies**
If using a Python environment, install required packages:
```bash
pip install -r requirements.txt
```

### **3️⃣ Run Sentiment Analysis (if scripts are provided)**
```bash
python sentiment_analysis.py
```

If there is no script yet, you can manually explore the **sentiment_scores.csv** in a Jupyter Notebook or Python environment.

---

## **📊 Deliverables**
- **Sentiment Analysis Report** – Examining trends in character dialogues.
- **NLP Sentiment Model** – Processing text data to analyze sentiment.
- **Data Visualizations** – Graphs showcasing sentiment fluctuations across the trilogy.

---

## **🔍 Key Insights**
This analysis provides valuable insights into:
- How **sentiment shifts throughout the trilogy**.
- Whether **emotional peaks align with major plot developments**.
- The portrayal of **the Skywalker family** across different movies.

These insights will be presented at **Comic-Con 2025**, helping Lucasfilm optimize content strategy based on **audience sentiment trends**.

---

## **👤 Contributors**
- **Andre Chuabio**
- Data sourced from **Star Wars Original Trilogy Scripts**
- Developed for **Case Study 3 (Your Course/Master’s Program Name)**

---

### **Next Steps for You**  
- **Review & Update the README**: Copy-paste this into your `README.md` file in GitHub.  
- **Ensure All Data Files Are Present**: Make sure `cleaned_dataset.csv`, `star_wars_trilogy_raw.csv`, and `sentiment_scores.csv` are correctly uploaded.  
- **Consider Adding Code or Visualizations**: I can generate **sentiment trend graphs** or provide **Python code** to analyze the data!  

---

