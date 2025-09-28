# Hotel Booking Cancellation Analysis

## Project Overview
This project explores patterns in hotel booking cancellations using the Hotel Booking Demand dataset. The goal is to analyze trends, visualize key insights, and optionally build a simple predictive model to estimate the likelihood of cancellations.

---

## Dataset
- **Source:** [Kaggle - Hotel Booking Demand](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand)
- **Description:** The dataset contains information on hotel bookings for two types of hotels (Resort and City) including:
  - Booking details (lead time, stay duration)
  - Guest details (number of adults, children, special requests)
  - Booking outcome (`is_canceled`)

---

## Project Structure
1. **Exploratory Data Analysis (EDA)**
   - Check for missing values
   - Analyze cancellation rates by hotel type
   - Visualize trends in booking data

2. **Key Insights**
   - Resort hotels generally have a lower cancellation rate than city hotels
   - Longer lead times are correlated with higher cancellation probability
   - Certain months have higher booking volume and higher cancellations

3. **Predictive Modeling (Optional)**
   - Built a simple Random Forest Classifier to predict cancellations
   - Used features: `lead_time`, `adr`, `stays_in_weekend_nights`, `stays_in_week_nights`, `total_of_special_requests`
   - Achieved decent prediction accuracy

---

## Technologies Used
- Python 3
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-Learn

---

## Next Steps
- Feature engineering for better model performance (e.g., seasonal trends, market segment)
- Hyperparameter tuning of the predictive model
- Deploy an interactive dashboard using **Streamlit** or **Plotly Dash** for exploration

---

## Author
**Kaley Wong**  
Data Analyst / Data Scientist  
[LinkedIn](https://www.linkedin.com/in/kaley-wong/) | [GitHub](https://github.com/your-github-username)
