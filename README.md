#  Trello REST API Automated Testing Suite (Postman)

## 📌 Project Overview
A comprehensive automated API testing suite for **Trello REST API** built using **Postman**. This project validates functional backend capabilities, HTTP status codes, payload integrity, and performance metrics across core Trello resources (Boards, Lists, and Cards).

---

##  Repository Files
*  **[Trello.postman_collection.json](./Trello.postman_collection.json)** - The complete Postman test collection.
*  **[Trello.postman_environment.json](./Trello.postman_environment.json)** - The parameterized environment variables file.

---

##  Tech Stack & Key Features
* **Tool:** Postman Desktop App
* **Environment Management:** Parameterized `{{key}}` and `{{token}}` variables to ensure zero hardcoded API credentials.
* **Test Automation:** Custom JavaScript scripts using Postman `pm.test()` & `pm.expect()` assertion libraries.
* **Test Scenarios:** Covered both Positive (Functional E2E) and Negative (Error Code Handling) flows.

---

##  Execution Evidence & Endpoints Coverage

###  Board Operations

* **Get All Boards:** Validated active workspace boards list and status `200 OK`.
  
  ![Get All Boards](API%20testing/Get_All_Boards.png)

* **Get Board By ID:** Verified specific board details extraction.
  
  ![Get Board By ID](API%20testing/Get_Board_By_ID.png)

* **Create New Board:** Handled board instantiation workflows.
  
![Create New Board](API%20testing/Create_New_Board.png)
* **Delete Board:** Executed board resource deletion and validated status `200 OK`.
  
  ![Delete Board](API%20testing/Delete_Board.png)
---

### List & Card Operations

* **Get Board Lists:** Retrieved all active lists associated with a target board.
  
  ![Get Board List](API%20testing/Get_Board_List.png)

* **Create New Card:** Created card instances under target list IDs.
  
  ![Create New Card](API%20testing/Create_New_Card.png)

* **Get A Card:** Verified details for a specific card entity.
  
  ![Get A Card](API%20testing/Get_A_Card.png)

* **Update A Card:** Tested `PUT` request modifications on existing card parameters.
  
  ![Update A Card](API%20testing/Update_A_Card.png)

* **Delete Card:** Executed resource teardown operations.
  
  ![Delete Card](API%20testing/Delete_Card.png)

---

## 👤 Author
**Mariam Mohamed**  
*Software Quality Assurance Engineer*
