# Company CRM App

This is a Customer Relationship Management (CRM) application for managing company data.

## Features

- [C]reate: Add new customers.

![app post_api_customers](https://github.com/missycoder/SCTP02-05-express-mysql-api/assets/156276105/1b168e28-2fce-42c3-a47f-1305e3dcfee7)

- [R]ead: Retrieve all customers.

![app get_api_customers](https://github.com/missycoder/SCTP02-05-express-mysql-api/assets/156276105/2266843d-c9eb-4cec-a408-e600d9dfbac8)
 
- [U]pdate: Update customer information.

![app put_api_customers](https://github.com/missycoder/SCTP02-05-express-mysql-api/assets/156276105/43f65d28-f0ff-4958-a635-3e1c9df5e6a2)

- [D]elete: Delete existing customers.

![app delete_api_customers](https://github.com/missycoder/SCTP02-05-express-mysql-api/assets/156276105/cbc72506-225e-4a77-b6d7-b3eab5cc440b)

## Back End Database

![MySQL Customers](https://github.com/missycoder/SCTP02-05-express-mysql-api/assets/156276105/58cd6475-546d-4be4-b07c-12e9d214a27e)

# ER Diagram
<img width="989" alt="crm_er_diagram" src="https://github.com/missycoder/MySQL-Customer-Relationship-Management/assets/156276105/80c20378-7c2c-4b63-97b3-d6f18795b4aa">

# CRM Diagram
![crm_diagram](https://github.com/missycoder/MySQL-Customer-Relationship-Management/assets/156276105/2ae1634a-90bd-4b90-9cce-19ac8e77d2cb)

## Installation

To run the application locally, follow these steps:

1. Clone the repository:
```bash
git clone <repository-url>

2. Navigate to the project directory:
cd express-mysql-api

3. Install dependencies
npm install

4. Set up the MySQL database by importing the provided SQL file

5. Start server:
npm start

6. Access the API endpoints using a REST client such as Postman or ARC

# To Run MySQL
To start mysql, in the terminal, type in `mysql -u root`

# Create a new database user
In the MySQL CLI:
```
CREATE USER 'ahkow'@'localhost' IDENTIFIED BY 'rotiprata123';
```

```
GRANT ALL PRIVILEGES on sakila.* TO 'ahkow'@'localhost' WITH GRANT OPTION;
```
**Note:** Replace *sakila* with the name of the database you want the user to have access to
 
 ```
FLUSH PRIVILEGES;
```
