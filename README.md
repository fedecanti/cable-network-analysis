# 📊 Cable Network Analysis & Prioritization

Python-based analysis and categorization system for 21,800 cable network segments (6,300 km) using time series analysis to identify high-priority sections for preventive maintenance.

## 📝 Project Overview

This project analyzes medium voltage cable network performance using historical failure and anomaly data to prioritize maintenance activities. The analysis processes multiple data sources to categorize 21,800 segments and identify 284 high-priority segments requiring immediate attention.

**Business Impact:**
- 📈 Analyzed **21,800 cable segments** covering **6,300 km** of network
- 🎯 Identified **284 high-priority segments** for preventive maintenance
- 🚀 **First initiative of this type** in the organization
- ⚡ Enables proactive maintenance planning and resource allocation
- 💰 Reduces network failures and improves service reliability

## 🛠️ Tech Stack

- **Python 3.x**
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical operations
- **OpenPyXL** - Excel file processing and formatting
- **PyArrow** - Parquet file handling

## 🗂️ Project Structure
```bash
cable-network-analysis/
├── README.md
├── requirements.txt
├── notebooks/
│ └── cable_analysis.ipynb # Main analysis notebook
├── data/
│ ├── input/ # Sample input files
│ └── output/ # Analysis results
└── images/
└── (optional screenshots)
```

## 🚀 How It Works

### 1. **Data Collection**
- Historical failure and anomaly data
- Network inventory (cables, transformers, installations)
- Geographic and operational data
- Planning and project information

### 2. **Analysis & Categorization**
- Time series analysis of failure patterns
- Anomaly detection and trend identification
- Risk scoring based on multiple factors
- Geographic and operational context integration

### 3. **Prioritization**
- Segments ranked by criticality
- Resource allocation recommendations
- Preventive maintenance planning
- Output formatted for operational use

## 📈 Key Features

- ✅ Processes multiple data sources (CSV, Excel, Parquet)
- ✅ Time series analysis for failure pattern detection
- ✅ Multi-factor risk scoring algorithm
- ✅ Automated categorization of 21,800+ segments
- ✅ Identifies high-priority maintenance targets
- ✅ Professional Excel output with formatting and tables
- ✅ Scalable to large network datasets

## 💻 How to Run

### Prerequisites

```bash
# Install required libraries
pip install -r requirements.txt
Execution
Place input files in data/input/:
4-Etapas.csv
Base Anomalias-Averias MT.xlsx
Dicc_INV.xlsx
Elementos_PYO.xlsx
Inventario_MT.parquet
Open and run notebooks/cable_analysis.ipynb
Output will be generated in data/output/Plan26.xlsx
```

📊 Results
Network Coverage:

21,800 cable segments analyzed
6,300 km of network coverage
Comprehensive risk assessment
Actionable Insights:

284 high-priority segments identified
Clear maintenance prioritization
Resource allocation guidance
Output Format:

Professional Excel report
Formatted tables and data
Ready for operational planning
🎯 Use Cases
This analysis supports:

Preventive Maintenance Planning: Identify cables before they fail
Resource Allocation: Prioritize maintenance crews and budgets
Risk Management: Focus on highest-impact segments
Strategic Planning: Long-term network improvement initiatives
Performance Tracking: Monitor network health trends
📝 Notes
Sample data provided represents the structure but not real business data
Original implementation analyzes complete network inventory
Time series analysis uses historical failure and anomaly patterns
First initiative of this type implemented in the organization
👤 Author
Federico Cantillana - Data Analyst & Team Lead
📧 Email: fede.canti@gmail.com
🔗 LinkedIn: linkedin.com/in/fede-canti
💼 Portfolio: [Your Notion Portfolio]