# AI-Based Expense Categorizer 🚀

This project automatically categorizes financial transactions into different spending categories (e.g., Food, Travel, Shopping, Bills) using AI.


## Tech Stack 
- Frontend: React (for UI)
- Backend: FastAPI (for API)
- AI Model: Scikit-Learn or TensorFlow (ML-based classification)
- Database: SQLite / PostgreSQL (to store transactions)
- Data Source: User uploads CSV or integrates bank APIs (e.g., Plaid for transactions)

## Features
- Upload Transactions: Users can upload CSV files with transaction history.
- AI-Powered Categorization: The model classifies expenses into categories.
- Manual Adjustments: Users can modify misclassified transactions.
- Analytics Dashboard: Display spending insights via graphs and charts.
- Recurring Expense Detection: Identify monthly subscriptions.

## Implementation Steps 

1. Data Collection 
    - User uploads CSV file with transaction history.

2. Data Preprocessing 
    - Clean the data and extract relevant features.

3. Model Training 
    - Use Scikit-Learn (Random Forest, Naive Bayes) or TensorFlow (Neural Networks).
    - Train a classifier to predict expense categories.

4. API Development (FastAPI) 
    - /upload → Accepts CSV files and processes data.
    - /categorize → Uses the trained model to categorize expenses.
    - /dashboard → Returns analytics data.

5. Frontend Development (React)
    - Upload Page: Users upload transaction files.
    - Dashboard: Displays categorized transactions and analytics.
    - Edit Page: Users can adjust category labels manually.