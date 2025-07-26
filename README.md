
# HealthKart Influencer Campaign Dashboard

This interactive dashboard helps analyze and generate insights from influencer campaign data, including influencer profiles, payouts, and user conversions.

## 🚀 Features

- Filter influencers by platform and gender
- Calculate and display metrics like ROAS (Return on Ad Spend)
- Export insights as CSV or PDF

## 📊 Technologies Used

- Python (Pandas, NumPy)
- Dash (Plotly)
- WeasyPrint (for PDF export)

## 📁 Project Structure

- `app.py`: Main Dash app with filters, data table, and export functionality
- `README.md`: This file

## 🛠 Setup Instructions

1. Clone the repository or download the project files.
2. Install the required packages:
    ```bash
    pip install pandas numpy dash weasyprint
    ```
3. Run the app:
    ```bash
    python app.py
    ```
4. Open jupyter notebook to view the dashboard.

## 📈 Key Metrics

- **Follower Count**: Total number of followers per influencer.
- **Total Payout**: Total payout given to each influencer.
- **Revenue**: Revenue generated via each influencer.
- **ROAS**: Revenue divided by total payout.

## 📤 Export

- Export data as CSV for offline analysis
- Generate a styled PDF summary of influencer performance

## 📄 Assumptions

- Revenue and order data are pre-aggregated.
- ROAS is calculated as: `revenue / total_payout`.

## 📌 Insights Summary (Sample)

| Influencer | Platform | ROAS |
|------------|----------|------|
| Alice      | Instagram| 1.8  |
| Bob        | YouTube  | 17.0 |
| Charlie    | Instagram| 1.94 |

## 🧠 Evaluation Criteria

- Data modeling & quality
- Analytical thinking (ROAS, incrementality)
- Product sense & storytelling
- Code quality and UX
- Documentation clarity

---
