# 📝 Notes App

A full-stack **Notes Application** built using **Next.js (App Router)**, **MongoDB**, and **Tailwind CSS**.  
The app allows users to create, view, update, and delete notes with a clean, modern, and animated UI.

---

## 🌟 Features

- ➕ Create new notes  
- 📄 View all notes  
- ✏️ Edit existing notes  
- 🗑️ Delete notes  
- 🕒 Automatic timestamps (createdAt & updatedAt)  
- 🎨 Dark theme with smooth animations  

---

## 🛠️ Tech Stack

- **Frontend:** Next.js (App Router), React  
- **Backend:** Next.js API Routes  
- **Database:** MongoDB Atlas  
- **ODM:** Mongoose  
- **Styling:** Tailwind CSS  
- **Version Control:** Git & GitHub  

---

## 📁 Project Structure

-  notes-app
-  ├── app
-  │ ├── api
-  │ │     └── notes
-  │ │           ├── route.js
-  │ │           └── [id]/route.js
-  │ ├── page.js
-  │ └── globals.css
-  ├── lib
-  │     └── mongodb.js
-  ├── models
-  │     └── Note.js
-  ├── .env.local
-  ├── .gitignore
-  └──package.json

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
  
#### bash
 git clone https://github.com/NitinBhadana05/notes-app.git
 cd notes-app

### 2️⃣ Install dependencies

  npm install
  
### 3️⃣ Environment Variables

  Create a file named .env.local in the project root:

#### env
  MONGODB_URI=your_mongodb_connection_string

### 4️⃣ Run the development server

#### bash
  npm run dev
  
#### Open browser: 
  http://localhost:3000

## 🧪 API Endpoints
### Method |	Endpoint	    | Description
  GET	   | /api/notes   	| Fetch all notes
  POST	 | /api/notes	    | Create a new note
  PUT	   | /api/notes/:id |	Update a note
  DELETE | /api/notes/:id	| Delete a note

##📚 What I Learned
Building a full-stack app using Next.js

Creating REST APIs with App Router

Connecting MongoDB using Mongoose

Performing CRUD operations

Debugging real-world issues

Using Tailwind CSS for modern UI

Managing environment variables securely

Using Git & GitHub professionally

## 🚀 Future Improvements
🔐 Authentication (login/signup)

👤 User-based notes

🔍 Search & filter notes

☁️ Deployment on Vercel

🔔 Toast notifications

## 👨‍💻 Author
Your Name
GitHub: https://github.com/NitinBhadana05

## ⭐ Acknowledgements
This project was built as a learning exercise to understand modern full-stack development using Next.js and MongoDB.

---
