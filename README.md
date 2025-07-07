# 🔐 Effective Login System with MongoDB Atlas

This project is a fully working **Login & Signup system** built with:

- HTML/CSS frontend  
- Node.js + Express backend  
- MongoDB Atlas (cloud database)  
- bcryptjs for secure password hashing  

---

## 📦 Project Structure

project-root/
├── server.js
├── .env
├── models/
│ └── User.js
├── public/
│ ├── login.html
│ ├── sign.html
│ └── welcome.html

yaml
Copy
Edit

---

## 🌐 Live Pages (After Starting the Server)

- 🔐 **Sign Up Page** → [http://localhost:5000/sign.html](http://localhost:5000/sign.html)  
- 🔑 **Login Page** → [http://localhost:5000/login.html](http://localhost:5000/login.html)  

---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone <your-repo-url>
cd project-folder
2. Install Dependencies
bash
Copy
Edit
npm install
3. Configure MongoDB Connection
Create a .env file in the root folder and add:

ini
Copy
Edit
MONGO_URI=mongodb+srv://<your_username>:<your_password>@cluster0.abcd.mongodb.net/myDatabase?retryWrites=true&w=majority
PORT=5000
Replace <your_username> and <your_password> with your MongoDB Atlas credentials.

✅ Running the App
bash
Copy
Edit
node server.js
You should see:

arduino
Copy
Edit
Server running on port 5000  
MongoDB Connected
📦 Features
User registration with hashed passwords

Secure login using bcryptjs

Success page redirection

MongoDB Atlas integration

Responsive HTML + CSS UI

📁 MongoDB Atlas
All user login/signup details are stored in your MongoDB Atlas database under the specified collection.
