# 🧠 Task 3: Feature Engineering - Restaurant Dataset

## 📌 Objective

The goal of this task is to enhance the dataset by extracting and encoding meaningful features from existing columns. Feature Engineering helps prepare the data for better visualization, interpretation, and potential machine learning applications.

---

## 🧪 Dataset Overview

The dataset contains information about restaurants including:
- `Restaurant Name`
- `Address`
- `Has Table Booking`
- `Has Online Delivery`
- `Aggregate Rating`
- `Price Range`

---

## ✨ Features Engineered

### 🔹 1. Length of Restaurant Name
A numerical feature `restaurant_name_length` was created by calculating the number of characters in each restaurant's name.

### 🔹 2. Length of Address
A numerical feature `address_length` was added to measure how long each restaurant's address string is.

### 🔹 3. Encoded "Has Table Booking"
A binary column `has_table_booking_encoded` was created:
- `1` = Yes  
- `0` = No

### 🔹 4. Encoded "Has Online Delivery"
A binary column `has_online_delivery_encoded` was created:
- `1` = Yes  
- `0` = No

---

## 🧰 Tools & Libraries

- **Python 3.x**
- **Pandas** – data processing
- **Google Colab** – code execution

---

## 📈 Sample Output

| restaurant_name | restaurant_name_length | address_length | has_table_booking | encoded | has_online_delivery | encoded |
|-----------------|------------------------|----------------|-------------------|---------|----------------------|---------|
| Domino's Pizza  | 15                     | 58             | Yes               | 1       | No                   | 0       |

---

## 🛠️ How to Run (in Google Colab)

1. **Upload dataset**:
```python
from google.colab import files
files.upload()
