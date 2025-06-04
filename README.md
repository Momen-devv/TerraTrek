# TerraTrek 🌍

TerraTrek is a modern, full-stack tour booking web application built with Node.js, Express, MongoDB, and JWT authentication.  
It allows users to explore and book exciting nature tours, manage their profiles, and leave reviews.

---

## 🚀 Features

- 🧭 Browse and filter tours
- 🔐 User signup, login, and secure authentication (JWT)
- 👤 Update user profile and change password
- 🌟 Leave reviews and ratings for tours
- 🛠️ Admin dashboard for managing users, tours, and bookings
- 📊 API features: filtering, sorting, pagination
- 💾 MongoDB database with Mongoose ODM

---

## 🛠️ Technologies Used

- Node.js
- Express.js
- MongoDB & Mongoose
- JWT (JSON Web Tokens)
- Postman (for API testing)
- Multer (for file uploads)
- Stripe (for payment integration) *(optional)*
- MongoDB Atlas (Cloud DB)

---

## 📂 Project Structure

```

project/
├── controllers/
├── models/
├── routes/
├── utils/
├── public/
├── dev-data/
├── config.env
└── server.js

````

---

## 📦 Installation

1. **Clone the repository**

```bash
git clone https://github.com/your-username/terratrek.git
cd terratrek
````

2. **Install dependencies**

```bash
npm install
```

3. **Create your `.env` file**

```env
NODE_ENV=development
PORT=3000
DATABASE=mongodb+srv://<your_mongo_connection>
DATABASE_PASSWORD=<your_password>
JWT_SECRET=your_jwt_secret
JWT_EXPIRES_IN=90d
JWT_COOKIE_EXPIRES_IN=90
```

4. **Run the app**

```bash
npm start
```

---

## 🧪 API Testing

Use [Postman](https://www.postman.com/) to test all routes.
Collection is available in the `postman/` folder (if provided).

---

## 📸 Screenshots

*(Add screenshots here if you have a frontend or Postman results)*

---

## 📚 Learning Reference

This project is built as part of the **Node.js Bootcamp** by [Jonas Schmedtmann](https://www.udemy.com/course/nodejs-express-mongodb-bootcamp/), with added customizations and enhancements.

---

## 📄 License

This project is for educational and personal portfolio purposes.

```
