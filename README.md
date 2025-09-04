#  Hotel Bookings Data Cleaning & EDA Project

##  Project Overview
This project is part of the **GTC ML Program**.  
The goal is to clean and preprocess the **hotel_bookings.csv** dataset, explore its structure, and prepare it for machine learning tasks.

---

##  Repository Contents
- `hotel_bookings.ipynb` → Jupyter/Colab notebook with all phases of the project.
- `hotel_bookings.csv` → The dataset used for analysis.
- `README.md` → Project documentation (this file).

---

##  Project Phases
### Phase 1: Exploratory Data Analysis (EDA)
- Generated `.info()` and `.describe()` statistics.
- Identified missing values using `missingno` and heatmaps.
- Detected outliers using boxplots and IQR.

### Phase 2: Data Cleaning
- Handled missing values (mode, median, replacement with 0).
- Removed duplicate rows.
- Capped extreme outliers (ADR, lead_time, stays, etc.).
- Fixed data types for date columns.

### Phase 3: Feature Engineering & Preprocessing
- Created new features: `total_guests`, `total_nights`, `is_family`.
- Encoded categorical variables (One-Hot & Frequency encoding).
- Removed leakage columns (`reservation_status`, `reservation_status_date`).
- Split dataset into training/testing sets (80/20).

---

##  How to Run
1. Open `hotel_bookings.ipynb` in **Google Colab** or Jupyter Notebook.
2. Make sure `hotel_bookings.csv` is in the same directory.
3. Run the notebook cells step by step.

---

 
