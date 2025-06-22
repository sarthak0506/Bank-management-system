Bank Management System
   
> Secure Command-Line Bank Management System
A Python CLI application simulating core banking operations with secure user authentication, account management, financial transactions
(deposits, withdrawals, transfers), transaction history, and an admin panel for oversight.

> Features
User registration, login, and password hashing.
Create and manage multiple savings/checking accounts.
Perform deposits, withdrawals, and inter-account transfers.
View detailed transaction history.
Admin panel: manage users (activate/deactivate), view all accounts and transactions.

> Technologies
Python 3.x
SQLAlchemy (ORM)
SQLite (Database)
bcrypt (Password Hashing)

> Getting Started
Clone the repository.
Create and activate a virtual environment:
python -m venv .venv

# Windows: .\.venv\Scripts\activate

# macOS/Linux: source ./.venv/bin/activate

# Install dependencies:
pip install sqlalchemy bcrypt

