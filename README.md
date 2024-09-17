# Expense Tracker

## Project Overview

The **Expense Tracker** is a simple application designed to help users manage their personal finances. It allows users to track their income, expenses, and budgets, along with categorizing their expenses and payment methods. The application is built using **Node.js** with a **MySQL** database and utilizes **Sequelize ORM** for database interaction.

---

## Features

- User Authentication
- Expense Tracking (with categories and descriptions)
- Budget Management (by category)
- Multiple Payment Methods Support
- Real-time expense reports

---

## Database Schema

The database includes the following tables:

1. **Users**: Stores user profile information
2. **Expenses**: Stores all the expense data
3. **Categories**: Defines various expense categories
4. **PaymentMethods**: Allows users to define different payment methods
5. **Budgets**: Helps users set and manage budgets for different categories

---

## Technologies Used

- **Node.js**: Backend framework
- **MySQL**: Relational database
- **Sequelize ORM**: Object-Relational Mapping tool for database interaction
- **Express.js**: Web framework for Node.js
- **bcrypt.js**: For password hashing and user authentication

---

## Installation and Setup

### Prerequisites

- Node.js (v14 or above)
- MySQL installed on your machine

### Steps to Install

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/expense-tracker.git
   cd expense-tracker
