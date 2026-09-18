# QA Technical Practice: API Testing & SQL Analytics

A technical showcase repository for a Junior / Strong Junior QA Engineer, demonstrating hands-on experience with REST API testing in Postman and relational database queries in SQL.

---

## 🚀 1. Postman API Testing Practice (DummyJSON API)
Automated API test collection created in Postman to validate CRUD operations, assertion status codes, and error handling for public endpoints.

### 🛠️ Key Features & Technical Scope
- **Full CRUD Coverage:** `GET`, `POST`, `PUT`, and `DELETE` HTTP methods.
- **Automated Assertions:** Status code validation (`200 OK`, `201 Created`, `400 Bad Request`, `404 Not Found`).
- **Environment Management:** Used environment variables (`{{baseUrl}}`) for dynamic, reusable, and scalable request building.
- **Negative Testing Scenarios:** Tested backend behavior for non-existent resources and invalid payload formats.
- **Test Execution:** Executed end-to-end collection runs using **Postman Collection Runner**.

### 📁 How to Run
1. Download or clone `API_postman_collection` from this repository.
2. Open **Postman** -> Click **Import** -> Upload the file.
3. Set an environment variable `baseUrl` = `https://dummyjson.com`.
4. Execute the suite via **Postman Collection Runner**.

---

## 🗄️ 2. SQL Data Analytics & Database Validation (Sakila DB)
Practical SQL scripts executed against the relational Sakila database (`sakila_sql_practice.sql`).

### 🛠️ Technical Scope & Query Types
- **Data Selection & Filtering:** Queries using `WHERE`, `ORDER BY`, and `LIMIT`.
- **Aggregations & Grouping:** Data analysis using `COUNT`, `SUM`, `AVG`, `GROUP BY`, and `HAVING`.
- **Multi-Table Relational Queries:** Extracting linked data using `INNER JOIN` and `LEFT JOIN`.
- **Data Integrity Checks:** Finding missing links and orphan records using `IS NULL`.
