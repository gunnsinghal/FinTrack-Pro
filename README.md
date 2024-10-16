# FinTrack Application

## Overview

This Application is a web-based tool developed using the Flask framework in Python. It allows users to track their daily expenses, categorize them, and visualize their spending habits over time.

## Features

- **User Authentication**: Secure login and registration system.
- **Expense Management**: Add, edit, and delete expenses.
- **Categories**: Categorize expenses for better tracking.
- **Reports and Analytics**: Generate reports to visualize spending patterns.
- **Responsive Design**: Works on both desktop and mobile devices.

## Installation

### Prerequisites

- Python 3.6 or higher
- Flask
- Virtualenv (recommended)

### Steps

1. **Clone the Repository**

   ```bash
   git clone https://github.com/<yourusername>/expense-tracker.git
   cd expense-tracker
   ```

2. **Create a Virtual Environment**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install Dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Set Up the Database**

   ```bash
   flask db init
   flask db migrate -m "Initial migration."
   flask db upgrade
   ```

5. **Run the Application**

   ```bash
   flask run
   ```

   Access the application at `http://127.0.0.1:5000`.

## Usage

1. **Register**: Create a new account.
2. **Login**: Access your account using your credentials.
3. **Add Expenses**: Navigate to the "Add Expense" section to log your expenses.
4. **View Expenses**: See a list of all logged expenses in the "View Expenses" section.
5. **Reports**: Generate and view reports to analyze your spending patterns.

## Project Structure

```
expense-tracker/
│
│   ├── app.py
│   ├── templates/
│   │   ├── base.html
│   │   ├── index.html
│   │   └── ...
│   ├── static/
│       ├── css/
│       ├── js/
│       └── ...
│
```


## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

