# 📊 ByteBalance – Personal Budget Tracker App

**ByteBalance** is an open-source Android app designed to help users—especially students—track their expenses, monitor spending habits, and reach savings goals using gamification and intuitive budgeting tools.

---

## 🧠 Purpose

Managing money can be overwhelming for students. ByteBalance makes it easy to:
- Record and categorize daily expenses
- Set and monitor monthly budget goals
- Visualize spending patterns over time
- Stay motivated through gamification

---

## 🚀 Features

- 📋 **Register & Login** – Secure authentication system for user access
- 💸 **Add Expense** – Add an expense with description, category, date, and optional photo
- 🗂️ **View Expenses** – Displays all expenses in a RecyclerView card layout
- 📅 **Set Budget Goals** – Users can set monthly spending limits
- 📈 **View Summary** – Filter and summarize spending by category, month, or date range
- 🏆 **Gamification (Planned)** – Earn rewards for meeting budget goals

---

## 🛠️ Tech Stack

- **Language**: Kotlin
- **IDE**: Android Studio
- **UI Framework**: Android Views (XML-based)
- **Database**: SQLite (via `SQLiteOpenHelper`)
- **Navigation**: Intents between Activities
- **Image Upload**: Optional image picker per expense

---

## 📂 Project Structure

ByteBalance/
├── app/
│ ├── java/com/example/bytebalance/
│ │ ├── activities/
│ │ │ ├── LoginActivity.kt
│ │ │ ├── RegisterActivity.kt
│ │ │ ├── DashboardActivity.kt
│ │ │ ├── AddExpenseActivity.kt
│ │ │ ├── ViewExpensesActivity.kt
│ │ │ └── ViewSummaryActivity.kt
│ │ ├── database/
│ │ │ └── DBHelper.kt
│ │ ├── model/
│ │ │ └── Expense.kt
│ │ └── adapter/
│ │ └── ExpenseAdapter.kt
│ ├── res/
│ │ ├── layout/
│ │ │ ├── activity_login.xml
│ │ │ ├── activity_register.xml
│ │ │ ├── activity_dashboard.xml
│ │ │ ├── activity_add_expense.xml
│ │ │ ├── activity_view_expenses.xml
│ │ │ └── activity_view_summary.xml
│ │ └── drawable/
│ │ └── button_green.xml

