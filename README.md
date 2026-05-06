# SQL Injection Lab

## 📌 Description

This project demonstrates a basic **SQL Injection vulnerability** in a login system.

The application takes user input and directly injects it into a SQL query without validation, allowing attackers to manipulate the query logic.

---

## ⚠️ Vulnerable Code

```php
$query = "SELECT * FROM users WHERE username = '$username' AND password = '$password'";