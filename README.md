InstaPay 

A lightweight, modular command-line banking and digital payment simulation written in Python. This application mimics key features of electronic payment platforms such as user registration, account authentication, card linking, deposits, withdrawals, peer-to-peer transfers, and transaction logging with robust input validation.

🌟 Features

User Authentication:

Secure registration with unique username checks.

Password and phone number formatting enforcement.

Account lockout mechanism after 3 failed login attempts.

Account Operations:

View current balance in EGP.

Deposit funds safely into your account.

Withdraw funds with instant balance verification.

Peer-to-peer money transfers with balance checks and recipient verification.

Change account password.

Card Linking:

Link Visa/Mastercard credit or debit cards.

Validates card details (16-digit number, MM/YY expiry date, 3-digit CVV).

Privacy-conscious: Validates CVV without storing sensitive security codes permanently.

Transaction History:

Detailed audit trail of deposits, withdrawals, and incoming/outgoing transfers.

📂 Project Structure

├── main.py        # Entry point containing the application loop and interactive menus
├── auth.py        # Authentication module (registration, login, and user lookup)
├── operations.py  # Core banking actions (deposit, withdraw, transfer, link card, etc.)
└── validation.py  # Validation utility functions for user inputs and credentials


🚀 Getting Started

Prerequisites

Python 3.6+ installed on your system.

Running the Application

Clone the repository:

git clone https://github.com/your-username/instapay-cli.git
cd instapay-cli


Run the application:

python main.py


💻 Usage Flow

Start the App: Launch main.py to open the main menu.

Register an Account: Select option 1 to create a new profile with a valid phone number (11 digits), username, and password (min 6 characters).

Log In: Select option 2 to authenticate using your registered credentials.

Perform Operations: Access features from the logged-in dashboard:

Check balance

Link a payment card

Deposit or withdraw EGP

Transfer money to another registered user

View your full transaction history
