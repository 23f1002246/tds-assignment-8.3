# Supply Chain Correlation Analysis

This repository contains the correlation matrix and heatmap visualization created from the supply chain performance dataset.  
The analysis follows Excel best practices from the *Visualizing Forecasts with Excel* module.

---

## 📁 Repository Contents

- **correlation.csv**  
  Correlation matrix generated using Excel’s Data Analysis ToolPak.

- **heatmap.png**  
  Excel-style correlation heatmap (Red–White–Green) created from the correlation matrix.  
  **Image size is under 512×512 pixels**, as required.

- **README.md**  
  Documentation and student identification.

---

## 👤 Student Email  
23f1002246@ds.study.iitm.ac.in

---

## 📝 Methodology

### 1. Dataset Import
- Supply chain dataset loaded into Excel.
- Variables included:
  - Supplier_Lead_Time  
  - Inventory_Levels  
  - Order_Frequency  
  - Delivery_Performance  
  - Cost_Per_Unit  

### 2. Correlation Matrix (Excel ToolPak)
- Enabled via:  
  **File → Options → Add-ins → Analysis ToolPak**
- Created using:  
  **Data → Data Analysis → Correlation**
- Selected all 5 columns with “Labels in first row” checked.
- Output directed to a new worksheet.

### 3. Heatmap Visualization
- Correlation matrix copied to a new sheet.
- Selected numerical values only (not labels).
- Applied Excel conditional formatting:  
  **Home → Conditional Formatting → Color Scales → Red–White–Green**  
  (Red = low correlation, Green = high correlation)

### 4. Output Export
- Correlation matrix exported as **correlation.csv**.
- Heatmap screenshot generated and resized to meet assignment requirement:  
  **400×400 px to 512×512 px** → saved as **heatmap.png**.

---

## ✅ Validation Requirements Checklist

| Requirement | Completed |
|------------|-----------|
| README includes email | ✔️ |
| correlation.csv created | ✔️ |
| heatmap.png (400–512px) | ✔️ |
| Red–White–Green formatting | ✔️ |
| All files ready for GitHub | ✔️ |

---

## 📄 Notes
All analysis was performed in Excel following the official module guidelines.  
The heatmap image was resized programmatically to comply with evaluation constraints.


