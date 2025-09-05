# GTC ML Project 1 - Hotel Bookings

This project is part of **GTC ML Project 1**.  
The goal is to clean and preprocess hotel booking data to prepare it for a cancellation prediction model.  

---

## 📂 Project Structure
- `hotel_bookings_project.ipynb` → Jupyter Notebook with all phases (EDA, Cleaning, Feature Engineering, Preprocessing).
- `hotel_bookings.csv` → Raw dataset (or a sample of it).
- `README.md` → Project documentation.

---

## 📊 Project Phases
### Phase 1: Exploratory Data Analysis (EDA)
- Summary statistics
- Missing values visualization
- Outlier detection using boxplots & IQR

### Phase 2: Data Cleaning
- Handle missing values (company, agent, country, children)
- Remove duplicates
- Handle outliers (cap adr)
- Fix data types

### Phase 3: Feature Engineering & Preprocessing
- Create new features (`total_guests`, `total_nights`, `is_family`)
- Encode categorical variables
- Remove data leakage columns
- Train/Test split

---

## 📌 Dataset
The dataset comes from the **Hotel Booking Demand Dataset**.  
Link: [Hotel Booking Demand on Kaggle](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand)

---

## 🛠 Tools & Libraries
- Python
- Pandas, Numpy
- Matplotlib, Seaborn, Missingno
- Scikit-learn

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/ayaalngar/gtc-ml-project1-hotel-bookings.git