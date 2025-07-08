# 🏕️ WanderNest – Discover Your Perfect Stay

**WanderNest** is a full-stack travel accommodation platform designed to help users explore, list, and review vacation properties. Built with **Node.js**, **Express**, **MongoDB**, and **EJS**, it provides a smooth, feature-rich experience that mimics real-world platforms like Airbnb — while remaining uniquely its own.

---

## 🌟 Name Inspiration

The name **WanderNest** combines two ideas:

- **Wander** – to travel and explore new places  
- **Nest** – a cozy, homely space to rest and stay

Together, WanderNest captures the essence of traveling to new destinations while finding comfort in well-curated stays.

---

## ✨ Features

- 🔍 Browse and search listings by category and keyword  
- 📝 Post and manage your own vacation property listings  
- 📆 Review booking dates and availability  
- 🖼️ Upload listing images via **Cloudinary**  
- 💬 Leave reviews and ratings for listings  
- 🔐 Secure login/signup with **Passport.js** (Google & Local)  
- 👤 User dashboard to manage profile and listings  
- 📩 Email confirmation (optional integration)

---

## 🔧 Tech Stack

**Backend**: Node.js, Express.js, MongoDB, Mongoose  
**Frontend**: EJS Templates, Bootstrap/CSS  
**Authentication**: Passport.js (Local + Google OAuth 2.0)  
**Image Hosting**: Cloudinary  
**Email Service**: Nodemailer (optional/integration-ready)

---

## 🚀 Project Goal

WanderNest aims to simulate a real-world travel platform experience. It's a great project for learning full-stack development — including authentication, cloud storage, RESTful routing, MVC patterns, and building secure user flows.

---

## 📁 Folder Structure (Optional)
```

WanderNest/
│
├── public/ ← Static assets (CSS, JS, images)
│
├── views/ ← EJS templates (pages, layouts, partials)
│
├── models/ ← Mongoose schemas (User, Listing, Review)
│
├── routes/ ← Modular route files (listings, users, reviews, categories)
│
├── utils/ ← Middleware, validators, error handlers
│
├── app.js ← Express app setup
│
└── .env ← Environment variables (Cloudinary, Google OAuth, etc.)
```

---

## ✨ Features

- 🏠 Browse listings and filter by category or keyword
- 🖼️ Upload and manage property images via Cloudinary
- 🔐 User authentication with Passport.js (Local + Google OAuth)
- ✍️ Leave reviews and ratings for listings
- 📂 User dashboard to view listings and reviews
- 🛠️ Server-side validation with Joi
- 💬 Flash messages for user feedback (success/error)
- ⚙️ MVC-based folder and routing structure

---

## 🛠️ Tech Stack

| Tech         | Usage                                |
|--------------|--------------------------------------|
| Node.js      | Backend runtime                      |
| Express.js   | Web framework                        |
| MongoDB      | NoSQL database                       |
| Mongoose     | MongoDB object modeling              |
| EJS          | Server-side templates                |
| Bootstrap    | Styling and responsive UI            |
| Cloudinary   | Image upload and storage             |
| Passport.js  | Authentication (Google + Local)      |
| Joi          | Schema validation                    |
| Nodemailer   | (Optional) email support             |

---

## 💻 Setup Instructions

### 🔧 Prerequisites

- Node.js & npm
- MongoDB (local or Atlas)
- Git

---

### 🛠️ Backend Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/maahirtaneja/WanderNest
   cd WanderNest
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3.Create a .env file in the root directory:
   ```bash
   CLOUD_NAME=your_cloudinary_name
   CLOUD_API_KEY=your_cloudinary_key
   CLOUD_API_SECRET=your_cloudinary_secret
   
   GOOGLE_CLIENT_ID=your_google_client_id
   GOOGLE_CLIENT_SECRET=your_google_secret
   GOOGLE_CALLBACK_URL=http://localhost:3003/auth/google/callback

   SESSION_SECRET=your_custom_session_key
   ```
4. Start the backend server:
   ```bash
   node server.js
   ```

## 📦 Deployment

You can deploy this full-stack project using:

### 🌐 Frontend
You can deploy the full app using:
	•	Render → Node.js server with automatic builds
	•	Railway / Cyclic / Heroku → Simple GitHub deployment
	•	Use environment variables from .env in your deployment dashboard

### ☁️ Image Storage
   •	Cloudinary → Upload and deliver images with secure URL access

### ☁️ Database
   •	MongoDB Atlas → Replace local URI in .env with your cluster URI for cloud hosting

---

## 🤝 Contributing

Contributions are welcome! If you'd like to:
- Fix bugs 🐞
- Add new features ✨
- Improve UI/UX 🎨
- Write tests 🧪

Just fork this repo, make your changes, and open a Pull Request. Let's make it better together!

---

## 📧 Contact

For any queries, feedback, or collaboration ideas:

- 📬 Email: [maahirtaneja@gmail.com](mailto:maahirtaneja@gmail.com)

---

© 2025 Maahir Taneja —  Built with ❤️ using Node.js, Express, and MongoDB

