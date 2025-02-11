# 340B Program Dashboard

An interactive dashboard providing insights into the 340B program. The dataset is generated programmatically using Python libraries **Faker** and **Pandas**, mimicking realistic trends in drug utilization, patient demographics, financial savings, and more.

---
## 📸 Dashboard Preview  
Here’s a preview of the **340B-Data-Analysis-Dashboard**:  

![340B Data Analysis Dashboard](PowerBi/Screenshot%202025-02-11%20162901.png)


## Table of Contents

1. [Features](#features)  
2. [Data Source](#data-source)  
3. [Installation](#installation)   



---

## Features

The dashboard includes the following insights:

### Financial Impact
- **Total Savings**: Savings generated from the 340B program.
- **Savings Percentage**: Percentage saved compared to regular prices.
- **Total Purchased Value**: Cost of drugs purchased under the program.

### Drug Utilization
- **Quantity Purchased vs Dispensed**: Track utilization rates.
- **Utilization Rate**: Efficiency of drug dispensation.

### Patient Demographics
- **Eligible Patient Count**: Patients served by the 340B program.
- **Patient Age and Gender Distribution**: Analyze accessibility trends.
- **Insurance Status**: Breakdown by insured vs uninsured patients.

### Location-Based Performance
- **Dispensing by Location**: Identify high-performing regions.
- **Savings by Location**: Evaluate cost-effectiveness regionally.

---

## Data Source

The dataset for this project was generated using the **Faker** library for simulating synthetic data and **Pandas** for data processing. These libraries helped create a realistic dataset with fields necessary for 340B program analysis.

### Key Fields
- `entity_id`, `entity_type`, `drug_id`, `drug_name`, `drug_category`
- `purchase_price`, `regular_price`, `quantity_purchased`, `quantity_dispensed`
- `eligible_patient_count`, `patient_age`, `patient_gender`
- `insurance_status`, `adverse_events`, `location`, `purchase_date`, `dispensing_date`

### Data Generation Script

The `generate_data.py` script generates the dataset:
- **Faker**: Simulates fields such as drug names, patient demographics, purchase dates, and dispensing dates.
- **Pandas**: Structures the data into a DataFrame for easy analysis and export.

---

## Installation

### Prerequisites
1. **Python 3.8+**
2. Required libraries:
   - `pandas`
   - `faker`
   - `numpy` (optional, for additional numeric processing)




