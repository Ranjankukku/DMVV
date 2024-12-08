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

<img width="1470" alt="Screenshot 2024-12-08 at 9 51 39 PM" src="https://github.com/user-attachments/assets/1a1ed8b2-067e-495a-a796-aecc94f51882">

### Question 4 Answers:

#### **Q 4(a)**

**(i) What visual communication goals are evident?**  
1. **Clarity:** The graphic aims to communicate information clearly and effectively.  
2. **Engagement:** It uses visual elements to capture the viewer's attention and make the information more appealing.

---

**(ii) Identify two (2) design principles and explain how the graphic applies them to fulfill the communication goals.**  
1. **Contrast:** The use of contrasting colors or shapes helps highlight key areas and ensures clarity by making important elements stand out.  
2. **Alignment:** Elements are organized in a structured manner, ensuring readability and guiding the viewer's focus effectively.

---

**(iii) The figure has been converted to greyscale. What colors would you recommend to use to highlight important points and why?**  
- **Red:** To draw attention to critical areas, as red is associated with urgency and importance.  
- **Blue:** To emphasize secondary points, as blue is calming and aids in readability.  
These colors ensure a clear hierarchy of information while maintaining visual appeal.

---

**(iv) Identify two (2) attributes that the graphic uses to encode data.**  
1. **Shape:** Different shapes represent distinct categories or ideas.  
2. **Size:** Variations in size indicate importance or quantity.

---

#### **Q 4(b)**

**Identify the gestalt principles of visualization present in each of the 3 images ([A], [B], [C]):**

- **[A]: Closure** – The brain perceives a complete shape even though parts are missing, completing the circle visually.  
- **[B]: Figure-Ground** – The image alternates between being perceived as a vase (figure) or two faces (ground).  
- **[C]: Continuity** – The dots form a smooth curve, leading the eye to follow the implied path.

---

#### **Q 4(c)**

**In some visualizations, size of objects represents a quantity. If using a 2D shape such as a circle to represent a quantity, what does the designer need to be careful of?**

The designer should ensure that:  
1. **Area, not diameter, represents quantity:** Viewers perceive size based on area, so scaling must be proportional to area rather than diameter to avoid misrepresentation.  
2. **Legibility:** Circles should not overlap excessively or be too small, ensuring clarity.

---

#### **Q 4(d)**

**Which is of greater importance in a visualization - luminance (brightness/contrast) or color (hue)? Justify your answer.**

- **Luminance (brightness/contrast)** is more important because:  
  - It defines visual hierarchy and ensures readability, even for viewers with color vision deficiencies (e.g., color blindness).  
  - Brightness differences are universally perceptible, while color perception varies across individuals and contexts.

<img width="1470" alt="Screenshot 2024-12-08 at 9 59 56 PM" src="https://github.com/user-attachments/assets/10b4d8d3-a0d6-4fe4-a45f-4e8dc319d2f4">



### **Answers to Question 3**

---

#### **Q3(a)**  
**(i) Example Metadata for a Pen:**  
- **Attributes:**
  - Color: Blue
  - Ink Type: Gel
  - Brand: Pilot
  - Length: 14 cm  

**(ii) Metadata Type:**  
- **Color:** Descriptive metadata (describes the physical appearance).  
- **Ink Type:** Administrative metadata (used for categorization).  
- **Brand:** Descriptive metadata (identifies the manufacturer).  
- **Length:** Structural metadata (provides physical dimensions).  

**(iii) Standard Usage for Metadata:**  
A standard like **Dublin Core** can be used to ensure consistency in describing and categorizing metadata attributes. For instance, it can define the format and vocabulary for describing attributes like color or ink type.  

**(iv) Problem with Enforcing Standards:**  
One major problem is **lack of universal adoption**, where different organizations or individuals may use varying standards, leading to inconsistency in data interoperability.

---

#### **Q3(b)**  
**Examples of Data Glitches and Their Impact on Decision-Making:**  

1. **Missing Data:**  
   - Example: Missing water usage data for certain months or areas.  
   - Impact: Decisions based on incomplete data could result in underestimating water demand, leading to resource shortages.  

2. **Duplicate Records:**  
   - Example: Duplicate entries for the same household's water usage.  
   - Impact: Overestimation of water usage, leading to incorrect allocation of resources or inflated costs.

---

#### **Q3(c)**  
**Three Possible Data Errors in the Table and Cleaning Methods:**  

1. **Error: Inconsistent Formatting (e.g., "6.2" in John’s January entry)**  
   - Cleaning Method: Standardize all numerical values to a consistent format (e.g., round to one decimal place).  

2. **Error: Missing Values (e.g., Sally’s May entry is blank)**  
   - Cleaning Method: Use imputation techniques such as filling with the average or median value for that column.  

3. **Error: Incorrect Totals (e.g., Total Expenses row does not match the sum of monthly values)**  
   - Cleaning Method: Recalculate totals based on corrected individual entries.

---

#### **Q3(d)**  
**Example of Sensitive Data Under GDPR Regulations:**  
- Personal data such as names, addresses, phone numbers, or financial details stored on a laptop.  

**Actions to Take After a Laptop Theft:**  
1. Notify the organization’s Data Protection Officer (DPO) immediately.  
2. Report the breach to relevant authorities (e.g., Data Protection Commission) within 72 hours if there is a risk to individuals' rights and freedoms.  
3. Inform affected individuals about the breach and advise them on protective measures (e.g., changing passwords).  
4. Investigate the breach internally and implement stronger security measures, such as encryption or two-factor authentication, to prevent future incidents.



