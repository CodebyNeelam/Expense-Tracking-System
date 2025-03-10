# Expense Management System

This project is an expense management system that consists of a Streamlit frontend application and a FastAPI backend server.


## Project Structure

- **frontend/**: Contains the Streamlit application code with five tabs.
- **backend/**: Contains the FastAPI backend server code.
- **tests/**: Contains the test cases for both frontend and backend.
- **requirements.txt**: Lists the required Python packages.
- **README.md**: Provides an overview and instructions for the project.

## Backend

The backend consists of:
- A **FastAPI** server that handles expense management operations.
- **Database-related files** for storing and retrieving expense data.
- APIs for adding, updating, and analyzing expenses.

## Frontend

The frontend consists of a **Streamlit** application with five tabs:

1. **Add/Update Expenses:**  
   - Allows users to enter daily expenses with details like amount, category, and notes.

2. **Summary by Category Analytics:**  
   - Provides a breakdown of expenses by category over a selected date range.
   - Visualized using bar charts and tables.

3. **Monthly Analytics:**  
   - Displays total expenses for each month.
   - Includes bar charts and a sortable table.

4. **Weekly Analytics:**  
   - (Upcoming feature) Shows expense trends on a weekly basis.

5. **Summary by Payment Mode Analytics:**  
   - Analyzes expenses based on different payment methods (cash, credit, digital wallets, etc.).
   - Includes pie charts and bar graphs for better visualization.


## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/expense-management-system.git
   cd expense-management-system
   ```
1. **Install dependencies:**:   
   ```commandline
    pip install -r requirements.txt
   ```
1. **Run the FastAPI server:**:   
   ```commandline
    uvicorn server.server:app --reload
   ```
1. **Run the Streamlit app:**:   
   ```commandline
    streamlit run frontend/app.py
   ```