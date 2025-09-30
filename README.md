#  Stock Market Monitoring & Simulation System

A **FinTech project** built for the **AWS AI Hackathon Hong Kong 2025**.  
This system enables users to **track live stock data**, **simulate trades with virtual money**, and **gain AI-powered insights** — making investing more **accessible, safe, and educational** for Hong Kong residents.

---

##  Problem Statement
In Hong Kong, many beginners and students face two barriers to investing:
1. **High risk** — trading without knowledge often leads to heavy losses.
2. **Lack of training platforms** — existing tools are expensive, overly technical, or intimidating.

---

##  Our Solution
The **Stock Market Monitoring & Simulation System** provides:
-  **Real-time stock tracking** (via Yahoo Finance API)
-  **Simulation mode** — trade with **virtual HKD balances**
-  **AI-powered “what-if” scenarios** (*e.g., what if I invested $1000 in Tech last month?*)
-  **Visual dashboards** — portfolio growth, risks, and performance
-  **Secure user accounts** — save and manage multiple portfolios

This empowers Hong Kong’s youth and professionals to **practice trading safely** before entering real markets.

---

##  How I Used Amazon Q Developer & Kiro

###  Amazon Q Developer
- Generated backend functions for **trade simulation & transaction handling**
- Reviewed code for **bugs, optimization, and security**
- Auto-generated **unit tests** for portfolio calculations
- Assisted in **AWS integrations** (SQLite backend now, future-ready for DynamoDB/API Gateway)

###  Kiro
- Applied **spec-driven development** → turned ideas into structured user stories
- Broke project into **task-level milestones** for collaboration
- Auto-generated **documentation and test cases**
- Improved workflow clarity throughout the build process

---
##  Learnign Contribution
- As part of this hackathon project, i also documented:
- Binary Trees for portfolio organization
- Shell Sort & Heap Sort for stock ranking 
- Matrix Data Structure for financial calculations

---
##  Tech Stack
- **Language**: Python 3
- **UI**: Tkinter + ttkbootstrap
- **Market Data**: yFinance
- **Visualization**: Matplotlib
- **Database**: SQLite
- **Persistence**: JSON & Pickle
- **AI Assistance**: Amazon Q Developer + Kiro








# You can install all the librarier at once by running the following command on your terminal:
# pip install -r requirements.txt


# Required Extensions and Libraries (If the `requirements.txt` file does not work, please manually install the libraries listed below.)

Required Extensions and Libraries
To run this project successfully, you will need to install the following Python libraries:

Tkinter
ttkbootstrap
yfinance
matplotlib
SQLite
json
pickle
sys
subprocess

You can install the required libraries using pip. Open your terminal or command prompt and run the following commands:
# for example 

pip install ttkbootstrap
pip install yfinance
pip install matplotlib


# Getting Started

1. Clone the Repository: Download or clone the repository to your local machine.
2. Install Required Libraries: Ensure you have all the required libraries installed as mentioned above.
3. Run the Application: Navigate to the project directory and run the main application file using Python.

`python main.py`

# Features

User Authentication: Users can create accounts, log in, and manage their portfolios securely.
Stock Simulation: Users can simulate buying and selling stocks with virtual capital.
Real-Time Monitoring: Users can monitor real-time stock prices and trends.
Portfolio Management: Users can view their stock holdings, transaction history, and profit/loss calculations.
Interactive Help: The application provides guidance on how to use various features.

# Usage

Upon launching the application, users will be presented with a login page.
New users can register by providing a username, password, and initial balance.
After logging in, users can access the main menu to navigate through different functionalities such as stock simulation, monitoring, and portfolio management.

