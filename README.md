# SmartBank
SmartBank is a comprehensive web application that enables users to manage accounts, perform transactions, and access banking services online securely and efficiently.


## Features

- User Registration & Authentication
- Account Management
- Fund Transfers
- Bill Payments
- Transaction History
- Responsive Frontend with Bootstrap
- Secure Backend with Django Rest Framework

## Live Demo

Check out the live demo of the SmartBank application here:  
[SmartBank Live Demo](https://nthasneem.pythonanywhere.com/)


## Steps to Install

  1. Clone the repository:
     ```bash
     git clone https://github.com/Nthasneem03/SmartBank.git
     ```
  2. Set up a virtual environment and activate it:
     ```bash
     python -m venv venv
     source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
     ```

  3. Install the required Python dependencies:
      ```
      pip install -r requirements.txt
      ```
  4. Run migrations to set up the database schema:
     ```
     python manage.py migrate
     ```
  5. Create a superuser for the Django admin interface:
      ```
      python manage.py createsuperuser
      ```
  6. Run the development server:
     ```
      python manage.py runserver
     ```
      Access the application at http://localhost:8000/.
      
## Usage
 - Register or log in to your SmartBank account.
 - Manage your bank account details and view your account balance.
 - Transfer funds between accounts.
 - Pay bills to various billers.
 - View your transaction history, including recent transactions and bill payments.
     
## Contributing
  Feel free to open issues or submit pull requests if you'd like to contribute to the project.

## Contact
For any queries or suggestions, feel free to reach out at naeemathasneem03@gmail.com.



