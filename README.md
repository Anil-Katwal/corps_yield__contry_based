# corps_yield__contry_based

<img width="1600" alt="Screenshot 2025-06-14 at 9 23 19 PM" src="https://github.com/user-attachments/assets/2e6f6342-282d-4a5d-b2b0-d314ce150f93" />

A machine learning project to predict crop yield based on environmental and agricultural factors such as rainfall, pesticide usage, temperature, and categorical features like Area and Crop Item.

---
## Web-app Demo
<img width="1182" alt="Screenshot 2025-06-14 at 9 42 23 PM" src="https://github.com/user-attachments/assets/b75dae8b-e8b3-422d-8d41-64b3d2958bfe" />
<img width="1161" alt="Screenshot 2025-06-14 at 10 07 05 PM" src="https://github.com/user-attachments/assets/7ded4a98-28c3-40d0-b9f6-e4bf4d01b18f" />

## Project Overview

This project uses a Random Forest regression model trained on crop-related data to predict the expected crop yield for given inputs. It demonstrates key ML concepts including:

- Handling mixed data types (categorical and numerical features)
- Preprocessing with `ColumnTransformer` for One-Hot Encoding and Standard Scaling
- Integration of the trained model and preprocessing pipeline into a Flask web API for real-time prediction

---

## Features

- Input features include:
  - **Categorical:** Area, Item (crop type)
  - **Numerical:** Year, Average rainfall (mm/year), Pesticide usage (tonnes), Average temperature (°C)
- Robust preprocessing pipeline using scikit-learn's `ColumnTransformer`
- Flask backend for serving predictions via HTTP POST requests
- Clear error handling and data validation to ensure proper data types and formats
- Modular code for easy updates and retraining

---

## Setup & Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Anil-Katwal/crop-yield-prediction.git
   cd crop-yield-prediction
