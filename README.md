**
---

### ✅ `server` README (`store-server` repo)

```NOT HOSTEd YET
# 🖥️ TravelBid - Server (API)

This is the backend of **TravelBid**, a secure Node.js/Express API that handles visa data using MongoDB and verifies user access via Firebase Authentication.

> ⚠️ Deletion is intentionally disabled to protect data integrity.

## 🔗 UI Repository

👉 [TravelBid Client Repo (React UI)](https://github.com/mehediScriptDev/Complete-store)

## 🛠️ Technologies Used

- Node.js
- Express.js
- MongoDB
- Firebase Admin SDK
- CORS
- Dotenv

## 📋 API Endpoints

| Method | Route     | Access     | Description             |
|--------|-----------|------------|-------------------------|
| GET    | `/visas`  | Protected  | Fetch all visa entries  |
| POST   | `/visas`  | Protected  | Add a new visa entry    |

## 🔐 Authentication

- Firebase Admin SDK verifies tokens from the frontend
- All endpoints are protected — only accessible after login

## 🧪 How to Run Locally

1. Clone this repo:
   ```bash
   git clone https://github.com/mehediScriptDev/store-server.git
**
