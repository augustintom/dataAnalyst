# DataForge – Automated Excel/CSV Analytics & Dashboard Generator

DataForge is a React-based data analytics and dashboard generation platform that allows users to upload Excel or CSV files and automatically transform raw data into interactive visual insights.

The application detects columns and data types, generates key performance indicators, creates interactive charts, provides searchable data tables, and offers additional analytical views such as Religion Analysis and World View.

It also includes a dedicated Admin Panel for managing website content from a centralized interface.

---

## 🚀 Features

### 📂 Excel & CSV Upload
- Upload `.xlsx`, `.xls`, and `.csv` files
- Read spreadsheet data directly in the browser
- Automatically detect headers and columns
- Handle blank or duplicate column names
- Convert uploaded data into an analytics-ready format

### 📊 Automated Analytics
- Automatic numerical and categorical data detection
- Total row and column calculation
- Sum and average calculations
- Dynamic KPI cards
- Automatic data analysis

### 📈 Interactive Data Visualization
- Dynamic charts using Chart.js
- Bar charts
- Line charts
- Data-based visual exploration
- Interactive analytical dashboards

### 🔎 Data Table
- Display complete uploaded datasets
- Search functionality
- Pagination
- Dynamic columns
- Easy data exploration

### 🌍 World View
- Geographic data visualization
- World map-based analysis
- Highlight selected or marked regions
- Visual representation of geographic insights

### 🛐 Religion Analysis
- Religion-related data analysis
- Categorization of religious data
- Visual comparison of available data
- Interactive analytical representation

### 🔄 Data Workflow

DataForge provides a structured workflow for data analysis:

1. Data Connection & Integration
2. Data Preparation & Cleaning
3. Calculated Fields & Logic
4. Visual Exploration
5. Dashboard Design & Interactivity
6. Publishing & Sharing

### 🛠️ Admin Panel
A separate Admin Panel is included for managing website content.

Admin features include:

- Manage website branding
- Edit navigation labels
- Edit dashboard content
- Edit upload page content
- Edit analytics page content
- Edit religion page content
- Edit world view content
- Edit workflow content
- Edit data table content
- Restore default content
- Save content changes

Admin URL:

```text
http://localhost:5173/admin

Excel / CSV File
       ↓
     Upload
       ↓
Spreadsheet Parsing
       ↓
Header & Data Detection
       ↓
Numerical / Categorical Detection
       ↓
Data Processing
       ↓
KPI Generation
       ↓
Interactive Charts
       ↓
Data Table
       ↓
Analytics & World View
