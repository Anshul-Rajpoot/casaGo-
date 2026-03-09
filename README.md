# casaGo 🏡

Live Demo: https://casago-ggz1.onrender.com

casaGo is a full-stack web application for discovering and sharing rental listings.  
Users can browse listings, create accounts, add properties, upload images, and leave reviews.

---

## 📸 Screenshots

<img width="1917" height="863" alt="image" src="https://github.com/user-attachments/assets/76f5a375-50a2-4333-8112-3e0a41dddbb5" />

<img width="1909" height="847" alt="image" src="https://github.com/user-attachments/assets/08b2c6be-3a5d-4dd4-87a1-374006151d6c" />

<img width="1896" height="871" alt="image" src="https://github.com/user-attachments/assets/9d3ec429-6cde-4813-b77d-d812c560323d" />

---

# 🚀 Features

- User Authentication (Signup / Login)
- Create, Edit, Delete Listings
- Image Upload with Cloudinary
- Reviews & Ratings System
- Session Authentication using Passport
- Flash Messages
- Responsive UI
- MongoDB Atlas Database
- Deployed on Render

---

# 🛠️ Tech Stack

Frontend:
- HTML
- CSS
- Bootstrap
- EJS Templates

Backend:
- Node.js
- Express.js

Database:
- MongoDB Atlas
- Mongoose

Authentication:
- Passport.js
- express-session

Image Storage:
- Cloudinary

Deployment:
- Render

---

# 📦 Installation Guide

Follow these steps to run the project locally.

---

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/Anshul-Rajpoot/casaGo-.git
cd casaGo-
```

---

## 2️⃣ Install Dependencies

Install all required packages using npm:

```bash
npm install
```

---

## 3️⃣ Create Environment File

Create a `.env` file in the root folder of the project.

```
.env
```

Add the following environment variables inside the file:

```
ATLASDB_URL=your_mongodb_atlas_url
SECRET=your_session_secret

CLOUD_NAME=your_cloudinary_name
CLOUD_API_KEY=your_cloudinary_api_key
CLOUD_API_SECRET=your_cloudinary_api_secret
```

---

## 4️⃣ Run the Application

```bash
nodemon app.js
```

or

```bash
node app.js
```

---

## 5️⃣ Open the Project

Open in browser:

```
http://localhost:8080
```

Listings page:

```
http://localhost:8080/listings
```

---

## 👨‍💻 Author

**Anshul Rajpoot**

GitHub:  
https://github.com/Anshul-Rajpoot
