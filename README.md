# Airport Management System (Oracle SQL)

A **comprehensive database project** designed to efficiently manage airport operations, covering aspects such as **airports, airlines, employees, flights, passengers, tickets, and baggage handling**.  
This project demonstrates **relational database design**, advanced SQL programming, and query optimization — ideal for showcasing strong **DBMS skills**.

---

## 📌 Features
- **Entity–Relationship Design**: 10+ normalized tables with proper relationships and constraints.
- **Stored Procedures**: Automates repetitive tasks (e.g., adding airports or airlines).
- **User-Defined Functions**: Retrieves statistics such as employee count per airport.
- **Triggers**: Enforces business rules and maintains data integrity.
- **Sample Queries**: Complex queries using `JOIN`, `GROUP BY`, and subqueries.
- **ER Diagram**: Clear visualization of database structure.
- **Comprehensive Report**: Project documentation and analysis in PDF format.

---

## 🛠 Technologies Used
- **Database**: Oracle SQL
- **Tools**: Oracle SQL Developer / Any SQL IDE
- **Modeling**: ERD design tools
- **Languages**: SQL (DDL, DML, DQL, TCL)

---

## 🚀 How to Run
1. **Install Oracle SQL Developer** or any compatible SQL client.
2. Open and execute the `AIRPORT_MANAGEMENT_SYSTEM.sql` file to create tables and relationships.
3. Optionally, run `sample_queries.sql` to test and explore the database.
4. Use the ER diagram for quick reference to the schema.

---

## 📊 Example Query
```sql
-- Get all flights for a given airline
SELECT f.flight_id, f.departure_time, f.arrival_time, a.airline_name
FROM Flight f
JOIN Airline a ON f.airline_id = a.airline_id
WHERE a.airline_name = 'Air India';

📄 Documentation
ER Diagram: ERD.png.png

Full Report: Project_Report.pdf


👤 Author
Savree Dohar



