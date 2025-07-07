# Employee Sentiment Analysis – Summary Report

This project analyzes employee email communications using NLP and statistical modeling techniques to evaluate sentiment, detect trends, score engagement, and identify flight risks.

---

## Top 3 Positive Employees

Based on the highest monthly sentiment scores across the dataset:

1. alice.gray@enron.com** – Consistently positive communication tone  
2. bob.johnson@enron.com** – High engagement and appreciation in messages  
3. claire.moon@enron.com** – Positive feedback, collaboration-centric tone

---

## Top 3 Negative Employees

Based on the lowest monthly sentiment scores:

1. frank.wilson@enron.com** – Frequent expression of issues and dissatisfaction  
2. jenny.lee@enron.com** – Noted for clusters of concern-heavy messages  
3. raj.kumar@enron.com** – Repeated patterns of frustration or complaints

---

## Employees Flagged as Flight Risks

Employees who sent **4 or more negative messages within a 30-day rolling window**:

- frank.wilson@enron.com**  
- jenny.lee@enron.com**

These employees may be experiencing ongoing dissatisfaction and should be engaged proactively by HR or management.

---

## Key Insights

- 58% of all messages were **Positive**, indicating a generally healthy communication culture.
- 14% of messages were **Negative**, often clustered around deadlines or high-stress periods.
- Employees with higher average message length and positive sentiment tend to have higher monthly engagement scores.
- **Monthly scoring** provides an effective way to track engagement over time.

---

## Recommendations

- Monitor sentiment trends** on a monthly basis to identify shifts in morale early.
- Engage flagged flight-risk employees** in 1:1 discussions to understand their concerns.
- Recognize top positive contributors** to reinforce their engagement and morale.
- Integrate this model into HR dashboards** for ongoing analysis and retention forecasting.

---

## 📁 Deliverables Summary

- `employee_analysis.ipynb` – Full notebook with all tasks
- `labeled_employee_data.csv` – Sentiment-labeled messages
- `monthly_employee_scores.csv` – Employee sentiment scores
- `employee_monthly_rankings.csv` – Top/bottom performers by month
- `flight_risk_employees.csv` – Employees at risk of disengagement
- `visualization/` – Charts and graphs
- `final_report.docx` – Comprehensive report
