# QXBroker Automated Trading Script

This Python script automates trading activities on the QXBroker website, providing users with a convenient way to execute trades automatically. The script is designed to log in, set profit targets, and execute trades based on predefined conditions, all while providing real-time monitoring of account balances and trade outcomes.

## Features

- **Seamless Login:** Log in to your QXBroker account seamlessly with your provided credentials.
- **Customizable Profit Targets:** Set your desired profit amount in dollars for automated trading sessions.
- **Dynamic Trade Execution:** The script dynamically adjusts trade amounts and directions based on previous trade outcomes.
- **Real-time Monitoring:** Keep track of your account balance and trade outcomes in real-time.

## Prerequisites

- Python 3.x
- Selenium library
- undetected_chromedriver library

## Usage

1. Clone the repository to your local machine.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Run the script and follow the on-screen instructions to set up your automated trading session.

## Configuration

Before running the script, make sure to update the following variables in the script:

- `user_email_address`: Your QXBroker account email address.
- `user_password`: Your QXBroker account password.
- `desired_profit_amount`: The desired profit amount in dollars for your trading session.
- `desired_user_id`: Your QXBroker user ID.

