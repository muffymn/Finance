# Finance: A Stock Portfolio
Project for Week 9 of Harvard's CS50
View the full assignment here: https://cs50.harvard.edu/x/2023/psets/9/finance/
![image](https://github.com/muffymn/finance.github.io/assets/110353148/e97ef711-86b0-47e6-8dcd-9241480d0b16)

# Technology Used
* Python
* Flask with session authentication
* SQL
* HTML
* Bootstrap

# Summary 
Finance is a web app that allows logged-in users to "buy" and "sell" stocks (with pretend money) as well as look up real stock quotes fetched from IEX API. Users can also view their stock portfolio transaction history.

# How To Run
1. Clone this repository, navigate to the project and type the following commands:
2. Activate a virtual environment: 'python3 -m venv .venv' then select the virtual environment as the active workspace
3. Install dependencies: 'pip install -r requirements.txt'
4. Run command 'export FLASK_APP=application.py' to set the Flask environment variable
5. [Configure and export your API key with these instructions](https://cs50.harvard.edu/x/2020/tracks/web/finance/#configuring)
6. Run command 'flask run' to open on localhost
7. When the finance site opens in your browser, register for a new account (upper right corner) to create your own stock portfolio
