# Vending Machine Backend System

This repository documents the architecture, database design, and implementation approach of a vending machine backend system developed as an academic project.

## 📝 Project Overview
Developed a functional backend system for a vending machine to process customer orders, calculate exact change, and securely store user data]. The project focuses on robust inventory management and transactional accuracy.

## 🛠️ Tech Stack
* **Language:** Python
* **Database:** MySQL
* **Logic/Domain:** Database Normalization, State Machine Logic, Transaction Processing

## ⚙️ Core Architecture & Features
* **Order Processing:** Automated calculation of total costs based on selected items.
* **Change Distribution Engine:** A mathematical algorithm that calculates the optimal denomination of coins/notes to return to the user.
* **Database Management:** Secure storage of user transactions, available inventory, and machine balance using relational data structures.

## 🗄️ Database Schema Design (MySQL)
* **`Inventory` Table:** `item_id`, `item_name`, `price`, `quantity_in_stock`
* **`Transactions` Table:** `transaction_id`, `user_id`, `item_id`, `amount_paid`, `change_returned`, `timestamp`
* **`Users` Table:** `user_id`, `encrypted_user_data`
