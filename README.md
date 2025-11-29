# 📊 Quilombo UK – Data Analysis Project

## 📌 Overview

This project investigates the factors associated with **underemployment in the United Kingdom**, using data from **Understanding Society (UKHLS)** for the **2021 and 2022** calendar years.

Underemployment is defined as a **mismatch between individuals’ potential (skills, qualifications, desired hours, or wage expectations) and the work they actually perform**. Although often invisible in standard labour statistics, underemployment has profound implications for:

- social mobility  
- income  
- career progression  
- mental health and well-being  

This project develops and analyses indicators of underemployment across demographic groups, with particular attention to **gender** and **migration status**.

---

## 🧭 Project Workflow

### **1. Data Extraction**
Relevant variables were extracted from the 2021 and 2022 waves of UKHLS. Columns include:

- employment status  
- education  
- occupation  
- hours worked  
- wages  
- well-being & satisfaction measures  

Additional migration-related variables were sourced from the **sub_data** files.

---

### **2. Data Cleaning & Merging**

Two main notebooks prepare the data:

- **main_data_edit.ipynb** – cleans each year's dataset and aligns variable names  
- **sub_data_edit.ipynb** – processes immigration-related variables  

After cleaning, datasets for **2021** and **2022** are merged to create a unified analytical dataset.

---

### **3. Analysis**

All analytical procedures are contained in:

- **analysis.ipynb** –  
  Includes construction of underemployment indicators, descriptive statistics, subgroup comparisons, and outcome assessments.

---

## 🧠 Conceptual Background: What Is Underemployment?

Underemployment occurs when individuals are working **below their potential**. This includes mismatches in skills, pay, hours, and job quality.

### **Types of Underemployment**

#### 🔹 Skills Underemployment (Overqualification)
When an individual's education or skills exceed the job requirements  
➡ Example: A university graduate working in a low-skilled role.

#### 🔹 Wage Underemployment
When hourly pay is lower than expected given one’s occupation, education, or labour market norms.

#### 🔹 Multiple or Combined Underemployment
Experiencing two or more disadvantages at the same time  
(e.g., low pay **and** working below skill level).

Underemployment is typically **involuntary** and is associated with:

- career stagnation  
- financial insecurity  
- poorer mental health  
- reduced job satisfaction  

---

## 👥 Study Population

### **Inclusion Criteria: Individuals who:**
- are aged **16–64**  
- are **employed or self-employed** at the time of the survey  
- provide valid data on education, occupation, hours, or wages  
- report **paid work** during the reference period  
- provide information relevant to underemployment or job satisfaction  

### **Exclusion Criteria**
Exclude individuals who are:

- full-time students whose main activity is study  
- retired or above statutory retirement age  
- working under external hour restrictions (e.g., visa limits)  
- voluntarily part-time and satisfied with their hours  
- unpaid family workers or volunteers  

---

## 🧩 Key Indicators to Construct

### **Goals**
- Develop consistent measures of underemployment  
- Test reliability across demographic groups  
- Compare indicators across years (2021–2022)

### **Indicators**
- **Skills mismatch**  
- **Wage mismatch**  
- **Combined/multiple underemployment**  
- **Perceived underemployment** (using satisfaction variables)

### **Validation Tasks**
- Verify logical consistency  
- Check frequencies by demographic subgroup  
- Investigate discrepancies between waves  

---

## 📈 Descriptive Analysis

### **Goals**
- Document patterns of underemployment in the UK  
- Identify differences across demographic groups  
- Explore relationships between underemployment, job satisfaction, and well-being  

### **Tasks**

#### 👤 Profile underemployment by:
- gender  
- migration status  
- education  
- disability status  

#### 🧠 Explore associations with:
- mental health indicators  
- job satisfaction (overall + specific dimensions)  

#### 🧹 Additional tasks:
- Compare different forms of underemployment  
- Record variable inconsistencies across years  

---

If you'd like, I can also:  
✅ Add a **table of contents**  
✅ Add **badges**, visuals, or graphs  
✅ Create a **Methods** or **Findings** section  
Just tell me!
