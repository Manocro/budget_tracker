**Budget Tracker**

A simple web app to track income and expenses, built with Java Spring Boot (backend) and vanilla HTML/CSS/JavaScript (frontend). (used to learn Java, javascript, HTML, and CSS)

📌 Table of Contents

Prerequisites

Features

How to Run

File Layout

✅ Prerequisites

IDE: IntelliJ IDEA (or any Java IDE)

Version Control: Git

Java: JDK 17+ (or latest)

🚀 Features

Add Income: Set amount, frequency, and date

Add Expense: Category, amount, date, notes, and optional recurring flag

Dashboard: Summary cards, pie chart, bar chart, and detailed lists

Filters: Client-side date-range and category filters

Settings: Light/Dark theme toggle and currency selection (saved locally)

Export: Download data as CSV or JSON

▶️ How to Run

Clone the repository:

git clone <repository_url>
cd budget-tracker

Build & Start the application:

mvn clean spring-boot:run

Or run the main class named BudgetTrackerApplication in IntelliJ.

Open a browser and go to:

http://localhost:8080

📁 File Layout

src/
  main/
    java/com/budgettracker/
      BudgetTrackerApplication.java
      BudgetController.java
      BudgetProfile.java
      Income.java
      Expense.java
      RecurringExpense.java
    resources/static/
      index.html
      dashboard.html
      add-income.html
      add-expense.html
      settings.html
      export.html
      dashboard.css
      dashboard.js
      add-income.js
      add-expense.js
      settings.js
      export.js
      background.gif



**Creators:**
Pranaya Pudasaini
Shawn Govitz
Manuel E De La Rosa Modesto

That's it! Feel free to explore and try out the features.
