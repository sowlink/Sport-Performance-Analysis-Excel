
# 📊 ** Sport-Performance-Analysis in Excel**  

This project involves analyzing dataset, called "NFL Combine Testing", focusing on **treatment and analsis, interpretataion of data, and visualization presentation**. 

---

## **📌 Project Overview**  
- **🎯 Objective**: to do the analysis of performance 
- **📂 Data Sources**:  
  - **`DataFrame`**: Testing profiles (Year, Names, College, POS, Height, Weight, 40 Yard(s) etc.).  

---

## **🛠 Lets figure out!**  

### **🔹 PART 1: Treatment and analysis **  

#### **1️⃣ How to define the missing data**  

- **Extract distinct test results** using **Add remarks(/NA) + Transpose**.  
- 
  ```excel
  ==IF(H2="", NA(), H2)
  ```  
1️⃣2️⃣3️⃣4️⃣5️⃣6️⃣7️⃣8️⃣9️⃣

---

### **🔹 PART 2: Interpretation of data**  
#### **1️⃣ Conditional formatting**  
#### **2️⃣ Effect size interpretation**  
#### **2️⃣ Smallest worthwhile change indicators** 
#### **4️⃣ Data Standardization **  
-  Use Z-score/ STEN Scores

---

### **🔹 PART 3: Visualization and presentation **  

#### **1️⃣ Pivot Table**  
Summarize athlete counts by **Year** and **Name** :  

- **Rows**: `Colle`  
- **Columns**: `Year`  
- **Values**: Count of `Name`  
- **Grand Totals** removed  

#### **2️⃣ Summary Table with Functions**  

- **Extract distinct test results** using **Add remarks(/NA) + Transpose**.  
- **Count athletes by year/college** using `COUNTIFS`:

---


## **📈 Key Insights**  

✔ **Data Relationships**: Athlete demographics and sports preferences vary by country (e.g., Germany dominates Alpine Skiing).  
✔ **Formatting**: Ensured consistency in **IDs, dates, and financial metrics** for readability.  
✔ **Automation**: Used **dynamic formulas (XLOOKUP, COUNTIFS)** to reduce manual updates.  
✔ **Tools Used**: **Excel Formulas, Pivot Tables, Conditional Formatting**  

---

🔗 **This project highlights advanced Excel data analytics skills, focusing on automation and insightful reporting.** 🚀
