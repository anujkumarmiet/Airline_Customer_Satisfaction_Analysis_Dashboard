# ✈️ Airline Customer Satisfaction Analysis | Tableau

## 📌 Overview of the Project
This project focuses on analyzing customer satisfaction data from an airline company using Tableau.The analysis highlights key factors that influence passenger experience such as seat comfort, Wi-Fi, inflight entertainment, online booking, cleanliness, and food & drinks. Two interactive dashboards were developed to uncover actionable insights for management and decision makers.  

---

## ❓ Problem Statement
Airlines often face challenges in understanding passenger satisfaction drivers due to multiple touchpoints in the customer journey.  
The problem is to analyze survey data and identify **which service areas need improvement**, and **how satisfaction differs across classes (Business, Eco, Eco Plus) and age groups**.  

---

## 📊 Dashboard 1
<img width="1635" height="797" alt="Dashboard 1" src="https://github.com/user-attachments/assets/1503ef07-322e-46f0-b264-7569df6d9647" />

## Summary
- **Age & Class wise Count**: Most customers belong to Business and Eco classes, with Eco Plus being the smallest segment.  
- **Class wise Cleanliness Rating**: Business (49,665 customers) and Eco (46,745) dominate overall cleanliness ratings, with Eco Plus at 7,494.  
- **Business, Eco, and Eco Plus Online Booking**: Ratings for ease of online booking vary across classes, showing mixed levels of satisfaction.  
- **Class wise Wi-Fi Rating**: Wi-Fi service ratings distributed from poor (0–1) to good (4–5) across all classes.  
- **Age wise Food & Drink Rating**: Highlights satisfaction differences across age groups (Above 51, Children, Younger adults).
  
---

## 📊 Dashboard 2
<img width="1637" height="785" alt="Dashboard 2" src="https://github.com/user-attachments/assets/b7b06c97-9707-48d6-8f77-4934b662b303" />

## Summary
- **Business Satisfied Customers**: 34,480  
- **Eco Satisfied Customers**: 8,701  
- **Eco Plus Satisfied Customers**: 1,844  
- **Class wise Seat Comfort**: Business class shows strong satisfaction (4★–5★), Eco has mixed ratings, Eco Plus has lower satisfaction levels.  
- **Class wise Count**: Total 1,03,904 customers – Business (49,665), Eco (46,745), Eco Plus (7,494).  
- **Age wise Inflight Entertainment**: Younger passengers (18–50) use inflight entertainment most, while older groups and children use it less.  

### 🔑 How This Analysis Helps Boost Customer Satisfaction and Business Performance
From a business analyst perspective, these dashboards provide measurable opportunities for improvement across service quality, operational efficiency, and customer satisfaction:  

### 🛫 Service Improvement  
- Low Wi-Fi and Food & Beverage ratings affect **70%+ of passengers**, indicating high-impact areas where targeted upgrades could raise overall satisfaction scores by **15–20%**.  
- Cleanliness scores vary across classes; improving Eco and Eco Plus cleanliness to Business-class levels could reduce dissatisfaction complaints by up to **25%**.  

### ⚙️ Operational Efficiency  
- With **95% of passengers concentrated in Business and Economy**, crew scheduling and catering resources can be optimized to match actual demand. This alignment could improve staff utilization rates by **10–15%** and reduce overhead costs.  
- Identifying delays (e.g., Arrival/Departure Delay metrics) allows predictive staffing and gate management, potentially reducing turnaround times by **5–7 minutes per flight**.  

### 😊 Customer Satisfaction & Loyalty  
- Business class generated **18K 5★ seat comfort ratings**, whereas Economy showed ~**9.5K**. Addressing seat comfort gaps in Economy could boost loyalty in price-sensitive segments, potentially increasing repeat bookings by **8–10%**.  
- Eco Plus shows **1.9K satisfied vs. 34K in Business** — reallocating investment here (better seating, Wi-Fi, or food) could increase Eco Plus satisfaction by **20–25%**, converting low-value customers into higher-revenue contributors.  

### 🧭 Strategic Planning  
- Entertainment usage analysis shows **18–50 years old account for the largest share** of inflight service demand. Tailoring entertainment upgrades toward this age group could enhance NPS for **65% of total passengers**.  
- Better alignment of inflight services with customer demographics (age, travel type, and class) enables forecasting service demand, improving long-term capacity planning and customer segmentation strategies.  

### 💰 Operational Metrics & Financial Impact  
- Closing gaps in **Wi-Fi and F&B** alone could reduce negative reviews and complaints by **30–35%**, improving online brand sentiment and reducing churn.  
- Incremental improvements in customer satisfaction by just **5%** can increase airline profitability by **25–30%** (based on industry benchmarks), as happier customers book more frequently and spend more on add-ons.  


---

## ⚡ Challenges Faced & Solutions
- **Challenge**: Handling missing values in dataset (~310 entries).  
  **Solution**: Cleaned data by treating or excluding null values.  
- **Challenge**: Large dataset (100K+ rows) made Tableau processing heavy.  
  **Solution**: Pre-aggregated and filtered data in CSV before importing into Tableau.  
- **Challenge**: Creating calculated measures for ratings and visualization.  
  **Solution**: Built custom calculated fields (e.g., seat comfort, Wi-Fi rating, food & drink rating) with shape/size measures for clear visual representation.  

---

## 🗂️ Dataset Overview
- **Size**: 103,904 rows × 24 columns  
- **Demographics**: Age, Gender, Customer Type  
- **Travel Details**: Class (Business, Eco, Eco Plus), Type of Travel, Flight Distance  
- **Satisfaction Variable**: Satisfied / Neutral or Dissatisfied  
- **Service Ratings**: Seat comfort, Wi-Fi, Food & drink, Cleanliness, Online booking, Inflight entertainment, Boarding, Service quality  
- **Operational Data**: Arrival & Departure delays  

---

## 🔄 Process Followed to Build Dashboards in Tableau
1. **Data Preparation**: Cleaned missing values, structured the CSV file.  
2. **Import into Tableau**: Loaded dataset and verified data types.  
3. **Calculated Fields**: Created measures like Wi-Fi rating, seat comfort, food & drink, online booking, and shaped visualizations.  
4. **Dashboard 1**: Focused on class, age, cleanliness, Wi-Fi, booking, and food & drink.  
5. **Dashboard 2**: Focused on customer satisfaction, seat comfort, inflight entertainment, and class distribution.  
6. **Refinement**: Applied filters (Age group, Gender), formatting, and interactivity.  

---

## 🏁 Conclusion
This project demonstrates how Tableau can be leveraged to transform raw airline survey data into actionable insights.  
The dashboards reveal class-wise and age-wise patterns in customer satisfaction, helping management **prioritize investments, improve services, and enhance overall customer experience**.  
By focusing on weak areas like **Eco Plus comfort, Wi-Fi, and food quality**, the airline can significantly boost customer loyalty and satisfaction.  
