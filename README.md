
---

### ✅ `server` README (`store-server` repo)

```markdown
# 🖥️ TravelBid - Server (API)

This is the backend of **TravelBid**, a secure Node.js/Express API that handles visa data storage using MongoDB and verifies user access via Firebase Authentication.

> ⚠️ Deletion is intentionally disabled to protect data integrity.

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

- Token verification via Firebase Admin SDK
- All endpoints are protected—users must be logged in to access

## 🧪 How to Run Locally

1. Clone this repo:
   ```bash
   git clone https://github.com/mehediScriptDev/store-server.git
