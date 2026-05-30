# Hotel-booking-analysis-Tableau
Analyzed 118K+ hotel bookings using Tableau to identify factors driving cancellations and revenue efficiency. booking behavior across hotel types, booking channels, lead time, waiting lists, customer segments, and geographic trends to provide actionable insights for improving occupancy, reducing cancellations, and optimizing revenue performance.
# 🏨 Hotel Booking Analysis Dashboard

## 📌 Project Overview

The primary business question for this project is:

**How can hotel booking operations reduce cancellations and improve revenue efficiency using booking behavior data?**

To answer this question, multiple analytical views were created to understand customer behavior, booking patterns, revenue drivers, and cancellation risks. The dashboard enables management teams to identify operational inefficiencies and take proactive actions to improve occupancy and revenue performance.

---

# 📊 Key Performance Indicators (KPIs)

| KPI                               |       Value |
| --------------------------------- | ----------: |
| Estimated Revenue                 | $12,157,618 |
| Lost Revenue (Cancelled Bookings) |    $461,943 |
| Average Daily Rate (ADR)          |      $101.8 |
| Total Bookings                    |     118,902 |
| Average Stay Duration             |    3.4 Days |
| Repeat Guest Percentage           |       3.19% |
| Cancellation Rate                 |         37% |

---

# 🔍 Business Questions Analyzed

1. Which months generate the highest revenue?
2. Which deposit type impacts bookings the most?
3. What is the impact of waiting time on cancellation rate?
4. Which hotel type experiences more cancellations?
5. Which booking channel performs best?
6. Which customer type stays the longest?
7. Which distribution channel affects cancellations?
8. Which hotel has better business performance?
9. Which countries generate the highest bookings?
10. What factors influence cancellations?
11. What is the average waiting period trend?
12. Which payment-related factors affect cancellations?

---

# 📈 Key Findings

## 1️⃣ Hotel Type Cancellation Analysis

A treemap visualization was used to compare cancellation rates between hotel types.

### Findings

* **City Hotel:** 41.73% cancellation rate
* **Resort Hotel:** 27.76% cancellation rate

### Insight

City Hotels experience significantly higher cancellations compared to Resort Hotels. This indicates that urban bookings may be more sensitive to changes in travel plans and booking behavior.

### Business Recommendation

Implement stricter cancellation policies and targeted retention campaigns for City Hotel bookings.

---

## 2️⃣ Booking Channel Performance Analysis

A horizontal bar chart was used to compare Average Daily Rate (ADR) across booking channels.

### Findings

| Booking Channel                 | Average ADR |
| ------------------------------- | ----------: |
| Online Travel Agent (Online TA) |       117.2 |
| Direct Booking                  |       115.4 |
| Aviation                        |       100.1 |
| Offline TA / TO                 |       Lower |
| Groups                          |        79.5 |

### Insight

Online Travel Agents and Direct Bookings generate the highest ADR and perform similarly well.

### Business Recommendation

Increase investment in high-performing channels while investigating why lower-performing channels generate lower revenue per booking.

---

## 3️⃣ Impact of Lead Time on Cancellation

A combination chart (bar + line) was created using lead time bins of 30-day intervals.

### Findings

* Cancellation rate increases as lead time increases.
* Around:

  * 540 days lead time → ~75% cancellation rate
  * 570 days lead time → ~100% cancellation rate
  * 600 days lead time → ~100% cancellation rate

### Insight

Customers booking far in advance are substantially more likely to cancel.

### Business Recommendation

Introduce deposit requirements or flexible pricing strategies for long lead-time reservations.

---

## 4️⃣ Impact of Waiting List Time on Cancellation

A histogram was created using 20-day waiting list intervals.

### Findings

* 20 days waiting list → 84.31% cancellation rate
* 100 days waiting list → 72% cancellation rate

Outliers above 250 waiting days were excluded to improve analysis quality.

### Insight

Long waiting periods are strongly associated with higher cancellation rates.

### Business Recommendation

Reduce waiting list durations and improve room allocation efficiency.

---

## 5️⃣ Hotel Business Performance Comparison

Comparison of ADR and cancellation rates between hotel types.

### Findings

| Hotel Type   |   ADR | Cancellation Rate |
| ------------ | ----: | ----------------: |
| City Hotel   |   105 |               42% |
| Resort Hotel | 94.95 |               28% |

### Insight

City Hotels generate higher revenue per booking but also experience significantly higher cancellation rates.

### Business Recommendation

Focus on reducing cancellations in City Hotels to maximize revenue efficiency.

---

## 6️⃣ Seasonal Booking Trends

Analysis of monthly booking behavior revealed clear seasonality patterns.

### Findings

* Peak demand occurs around May and October.
* Lower activity appears during periods associated with school and work schedules.
* Average waiting periods exceed 4 days during peak months.

### Insight

Demand fluctuations follow predictable seasonal patterns.

### Business Recommendation

Adjust pricing, staffing, and room availability based on expected seasonal demand.

---

## 7️⃣ Geographic Booking Analysis

### Findings

Top booking country:

* Portugal (PRT): 48,590 bookings

Second highest:

* 12,129 bookings

### Insight

A significant proportion of bookings originate from Portugal, likely reflecting domestic demand concentration.

### Business Recommendation

Continue strengthening domestic marketing efforts while identifying opportunities for international growth.

---

# 🎯 Overall Conclusion

The analysis highlights that cancellation behavior is heavily influenced by lead time, waiting list duration, hotel type, and booking channel.

Key opportunities for improving operational efficiency include:

* Reducing long waiting periods
* Managing high lead-time reservations more effectively
* Strengthening high-performing booking channels
* Addressing high cancellation rates in City Hotels
* Leveraging seasonal demand trends for better planning

These insights enable hotel management and marketing teams to make data-driven decisions that improve revenue efficiency, reduce cancellations, and optimize overall booking performance.

---

## 🛠 Tools Used

* Tableau
* Excel
* Data Cleaning
* Exploratory Data Analysis (EDA)
* Business Intelligence & Dashboarding
* Hotel Booking Dataset Analysis
