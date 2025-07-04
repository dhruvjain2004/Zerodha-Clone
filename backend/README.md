# Zerodha Backend API

Node.js backend API for the Zerodha trading platform clone.

## 🚀 Quick Start

1. **Install dependencies:**
   ```bash
   npm install
   ```

2. **Set up environment variables:**
   Create a `.env` file:
   ```env
   MONGO_URL=mongodb://localhost:27017/zerodha
   JWT_SECRET=your_jwt_secret_key_here
   PORT=3002
   NODE_ENV=development
   ```

3. **Start the server:**
   ```bash
   npm run dev
   ```

## 📁 Project Structure

```
backend/
├── controllers/         # API controllers
├── middlewares/         # Authentication middleware
├── models/             # MongoDB models
├── schemas/            # Database schemas
├── AuthRoute.js        # Authentication routes
├── index.js            # Main server file
└── package.json        # Dependencies
```

## 🔧 API Endpoints

### Authentication
- `POST /api/auth/register` - Register new user
- `POST /api/auth/login` - User login

### Trading Data
- `GET /allHoldings` - Get user holdings
- `GET /allPositions` - Get user positions
- `GET /allOrders` - Get user orders
- `POST /addNewOrder` - Add new order (requires auth)

### Health Check
- `GET /health` - Server health status

## 🛠️ Technologies

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- bcryptjs
- CORS

## 🔒 Security

- JWT token authentication
- Password hashing
- Input validation
- Error handling
- CORS configuration #   J u s t   a   d u m m y   c h a n g e  
 