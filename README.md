# daily-expense-tracker
# Expense Analysis Report Generator
This project analyzes your expense data from a CSV file and generates a PDF report with visual charts and key statistics.
## Input
- A CSV file named `expenses.csv`.
- Date,Category,Amount,2025-01-01,Food,200,2025-01-01,Transport,100 ...

## 📈 Output
- **Console Output** showing:
- Spending by category
- Daily expenses
- Highest spending day
- Average daily spending

- **Visual Charts:**
- Bar chart of total spending by category (`catagory_total.png`)
- Line chart of daily spending trend (`daily_total.png`)

- **PDF Report:**
- File: `expense_analysis_report.pdf`
- Includes:
  - Total spending by category
  - Highest spending day
  - Average daily spending
  - Embedded charts for clear insights
## 🛠️ How It Works
1. Reads and processes your expense data using **Pandas**.
2. Generates summary statistics.
3. Visualizes trends using **Matplotlib**.
4. Compiles a clean PDF report with **FPDF**.

## ✅ Key Outcomes
- Get a quick understanding of where your money goes.
- Spot the most expensive day and category.
- Track daily spending trends over time.
- Have a professional report ready for record-keeping or sharing.

![dailyspend](https://github.com/user-attachments/assets/52ac7efc-d108-492d-be09-9f1cc207d8bc)
![totalspend](https://github.com/user-attachments/assets/5e3b7195-7b75-421a-b8c5-0142406949ab)
