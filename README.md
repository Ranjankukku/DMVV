describe how the data may have been Gathered, Processed, Analysed, Presented and Preserved. Give a brief description of the activities at each stage (1-2 sentences) and identify any specific tools that you did or would use.

---

### **1. Gathering**
- **Activities**: Data is collected from relevant sources. For heart attack prediction, this may involve extracting patient data (e.g., cholesterol, blood pressure, BMI, triglycerides, etc.) from electronic health records or surveys. For student feedback, data could be gathered via online surveys or institutional feedback forms.
- **Tools**: Excel for manual data entry; SQL for querying databases; Google Forms or SurveyMonkey for collecting feedback.

---

### **2. Processing**
- **Activities**: Data cleaning and transformation are performed to ensure consistency and quality. This includes handling missing values, correcting errors, and standardizing formats (e.g., normalizing cholesterol levels into categories like "Desirable," "High").
- **Tools**: Python (using pandas or NumPy for cleaning), Tableau Prep for ETL (Extract, Transform, Load), or Excel for simple transformations.

---

### **3. Analysis**
- **Activities**: Statistical and exploratory analysis is conducted to identify trends, correlations, and patterns. For heart attack prediction, this could include identifying correlations between cholesterol levels, triglycerides, and heart attack risk. For student feedback, sentiment analysis might be performed to understand satisfaction levels.
- **Tools**: Python (using libraries like matplotlib, seaborn, or scikit-learn), R for statistical analysis, or Tableau for visual exploration.

---

### **4. Presenting**
- **Activities**: Insights are communicated through visualizations and reports. For heart attack prediction, scatter plots can show relationships between cholesterol and heart attack risk; bar charts can compare BMI categories. For student feedback, dashboards can display satisfaction trends over time.
- **Tools**: Tableau for creating interactive dashboards; PowerPoint for presentations; Canva for designing infographics.

---

### **5. Preserving**
- **Activities**: The processed data and insights are stored securely for future use. This involves maintaining data integrity and ensuring compliance with privacy regulations (e.g., GDPR for health data or student feedback).
- **Tools**: Cloud storage solutions like Google Drive or AWS S3; databases like PostgreSQL; version control tools like GitHub for storing scripts and reports.

---

This pipeline ensures a systematic approach to analyzing any dataset while leveraging appropriate tools at each stage to maximize the quality of insights and their usability over time.

Sources
[1] Heart_attack_datasets.xlsx https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/41669035/0fa97648-97ad-48b6-a0c6-aef2ce6d7892/Heart_attack_datasets.xlsx
[2] Ten things to know about ten cardiovascular disease risk factors https://pmc.ncbi.nlm.nih.gov/articles/PMC9061634/
[3] Electronic healthcare records and external outcome data for ... - Nature https://www.nature.com/articles/s41597-021-00835-9
[4] Heart disease: key data sources - Scottish Public Health Observatory https://www.scotpho.org.uk/health-conditions/coronary-heart-disease/key-data-sources/
[5] Cardiovascular Diseases - Our World in Data https://ourworldindata.org/cardiovascular-diseases
