# ALX Book Store Database Project

## Project Overview

This project is a MySQL database for an online bookstore. It includes scripts to create the database, create tables, insert data, and view table information.

## Database Name

`alx_book_store`

## Tables

- **authors**: author_id, author_name
- **books**: book_id, title, author_id, price, publication_date
- **customers**: customer_id, customer_name, email, address
- **orders**: order_id, customer_id, order_date
- **order_details**: orderdetailid, order_id, book_id, quantity

## Project Files

- `alx_book_store.sql` – create database
- `MySQLServer.py` – Python script to create database
- `task_2.sql` – create all tables
- `task_3.sql` – list all tables
- `task_4.sql` – describe `books` table
- `task_5.sql` – insert a single customer
- `task_6.sql` – insert multiple customers

## Usage

1. **Create database (Python)**

```bash
python3 MySQLServer.py
```

2. **Create tables**

```bash
mysql -u root -p alx_book_store < task_2.sql
```

3. **List tables**

```bash
mysql -u root -p alx_book_store < task_3.sql
```

4. **View table structure**

```bash
mysql -u root -p alx_book_store < task_4.sql
```

5. **Insert single customer**

```bash
mysql -u root -p alx_book_store < task_5.sql
```

6. **Insert multiple customers**

```bash
mysql -u root -p alx_book_store < task_6.sql
```
