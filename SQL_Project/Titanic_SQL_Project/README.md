# 🚢 Titanic Survival Analysis Using SQL

This project analyzes survival patterns of passengers on the Titanic using SQL. It includes database creation, data insertion, and multiple queries to explore survival rates based on class, gender, and fare.

---

## 📁 Project Files

- `TitanicSql.sql` – Full SQL script including:
  - Database and table creation
  - Data insertion (passenger records)
  - Views for survival count, class-wise fare, gender survival, and record verification
- `README.md` – Project overview and explanation

---

## 🧾 Table Structure

**Table Name:** `Survived`  
Includes columns for:
- `PassengerId` (INT, UNIQUE)
- `Pclass` (INT)
- `PassengerName` (VARCHAR)
- `Sex` (ENUM: 'male', 'female')
- `Age` (INT, default 0)
- `Ticket_Fare` (DECIMAL)
- `Embarked` (CHAR)
- `Survived` (INT, 1 = Yes, 0 = No)

---

## 📌 SQL Views Created

- `Surv` – View of all data  
- `count_check` – Total number of records  
- `tot_surv` – Total number of passengers who survived  
- `tot_sex` – Gender-wise survival count  
- `Tot_Fare` – Class-wise total fare collected

---

## 🛠 Tools Used

- MySQL / SQL Server / DB Browser for SQLite
- Titanic dataset (subset of real passenger data)

---

## 📊 Sample Insights

- More females survived than males.
- First-class passengers had a higher chance of survival.
- Pclass 3 had the lowest total fare collection but highest passenger count.

---

## ✅ How to Use

1. Open the SQL file in your SQL environment.
2. Run the script step-by-step to:
   - Create the database and table
   - Insert sample data
   - Create views and run queries

---

## 📚 Conclusion

This project demonstrates how SQL can be used for data cleaning, querying, and generating insights — ideal for beginner-level data analyst roles.
