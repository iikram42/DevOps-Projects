## Java Login App ##
Testing 

## Sample Java Login application uses "UserDB" database and Table schema to store the Employee Login details. ##

## How to see list of Databases ##
SHOW DATABASES;

## How to create Database ##

CREATE DATABASE UserDB;

## How to list Tables ##

USE UserDB;

SHOW TABLES;

## How to create Table ##
## Below Query to create require TABLE schema to store Employee records ##

CREATE TABLE Employee (
  id int unsigned auto_increment not null,
  first_name varchar(250),
  last_name varchar(250),
  email varchar(250),
  username varchar(250),
  password varchar(250),
  regdate timestamp,
  primary key (id)
);

## List Table data ##
SELECT * FROM Employee;

## Describe Table schema ##
DESCRIBE Employee;


## 🛠 Author

This project is maintained by **[Syed Ikramuddin Kirmani](https://github.com/iikram42)** 💡.  
Your feedback and contributions are welcome!

📧 *Connect with me:*
- *GitHub*: [@iikram42](https://github.com/iikram42)
- *LinkedIn*: [Syed Ikramuddin Kirmani](https://www.linkedin.com/in/ikramkirmani/)

---

## ⭐ Support the Project

If you found this project helpful, please consider:
- *Starring* ⭐ the repository  
- *Sharing* it with your network  
- *Contributing* to its improvement

> [!Important]  
> This documentation is continuously evolving. For the latest updates, please check the repository regularly.
