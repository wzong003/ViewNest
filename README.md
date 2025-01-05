**Real Estate Management System
**

This repository contains the source code for a Real Estate Management System, developed as part of a group project for UOW-SIM CSIT 314.
The system is designed to support key functionalities for real estate agents, buyers, sellers, and admins in a property management ecosystem. The system was developed using object-oriented programming principles and follows the Agile methodology to ensure iterative progress and continuous improvement.

Key Features
The Real Estate Management System includes the following features:

User Management: Supports various user types including System Admin, Real Estate Agents, Sellers, and Buyers. Each user type has specific roles and permissions.
Property Listings: Real estate agents can create, update, and remove property listings. Buyers can search, view, and save properties to a favorite or shortlist.
Seller Analytics: Sellers can track the performance of their properties, including metrics such as view count and number of times shortlisted.
Mortgage Calculator: Buyers can calculate potential mortgage payments based on property price, interest rates, and other relevant financial factors.
Ratings and Reviews: Buyers and sellers can rate and review real estate agents, ensuring transparency and trust within the platform.
Data Generation
Test Data: To simulate real-world usage, the system includes test data for various functionalities. The system is populated with 100+ records for each data type (properties, users, etc.), generated using a custom script to ensure scalability during testing.
Development Process

Create a virtual environment to manage project dependencies:
python -m venv venv

For Windows:
venv\Scripts\activate

For macOS/Linux:
source venv/bin/activate

Install the required Python packages.:
pip install flask SQLAlchemy flask-babel sqlalchemy
python -m pip install --upgrade pip
