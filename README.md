# job-expectation-data-preparation

## 📘 Overview
This project aims to automate the collection and preparation of candidate profile data to study changing job expectations.  
Using **n8n** and **Google Search API** the workflow collects public LinkedIn profile data, extracts text information and stores structured results for further analysis.

At this stage, the project focuses on the **data collection and preprocessing phase**.

---

## ⚙️ Tech Stack
- **n8n** – workflow automation and API orchestration  
- **Google Search API** – query and retrieve LinkedIn profile URLs  
- **spaCy** – text extraction and preprocessing  
- **Google Sheets** – data storage and organization  

---

## 🚀 Workflow Summary
1. **Search & Retrieve Profiles**  
   - Use Google Search API within n8n to query LinkedIn profile URLs related to specific job keywords.  

2. **Extract & Store Data**  
   - Extract relevant text (e.g., About section, descriptions) from the profiles.  
   - Store the extracted data in Google Sheets.  

3. **Preprocess Text**  
   - Apply spaCy for text cleaning and tokenization.  

---

## 📈 Current Progress
- ✅ Workflow setup in n8n  
- ✅ Data collection completed  
- ✅ Basic text extraction using spaCy  
- 🔄 Next step: Perform text analysis and visualization  

---

## 📊 Example Output

---

## 🗂️ Future Work
- Conduct exploratory text analysis to identify themes and trends.  
- Visualize keyword frequency and candidate expectations over time.  

---
