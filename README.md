# Postman API Testing Practice Project

Automated API test suite created in Postman to validate CRUD operations and error handling for the DummyJSON public API.

## 🛠️ Key Features & Technical Scope
- **Full CRUD Coverage:** `GET`, `POST`, `PUT`, `DELETE` requests.
- **Automated Assertions:** Status codes validation (`200 OK`, `201 Created`, `404 Not Found`, `400 Bad Request`).
- **Environment Management:** Utilized environment variables (`{{baseUrl}}`) for dynamic and scalable request building.
- **Negative Testing Scenarios:** Validated backend handling for non-existing resources and invalid payload types.
- **Test Automation:** Executed end-to-end collection runs using **Postman Collection Runner**.

## 📁 How to Run
1. Download or clone `API_postman_collection` from this repository.
2. Open **Postman** -> Click **Import** -> Upload the file.
3. Set an environment variable `baseUrl` = `https://dummyjson.com`.
4. Run the collection using Postman Collection Runner.
