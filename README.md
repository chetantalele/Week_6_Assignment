# RESTful API using Node.js, Express, and MongoDB

This project is a simple RESTful API built using **Node.js**, **Express.js**, and **MongoDB**. It supports basic CRUD operations on two resources: **Users** and **Products**.

The project is developed as part of **Celebal Technologies – Week 6 Assignment**.

## ⚙️ Configuration

Make sure to **update the MongoDB connection URL** in the `server.js` file:

```js
mongoose.connect('your-mongodb-url-here', {
  useNewUrlParser: true,
  useUnifiedTopology: true
});
