<h1 align="center">
  <br>
  URL-Shortener 🔗
  <br>
</h1>

<p align="center">
  A URL shortening application developed using the MERN stack for an efficient and modern web experience.
</p>

<div align="center">
  <img src="./client/src/assets/ss.png" alt="URL Shortener screenshot" width="900">
</div>

---

## 🎬 Demo Video

[URL-Shortner](https://www.linkedin.com/posts/soumadip-majila-dgp_just-built-a-sleek-url-shortener-with-mern-activity-7365975588794191872-rLcA?utm_source=social_share_send&utm_medium=member_desktop_web&rcm=ACoAAD1aMJQBxnv5DdAHrtZuCweFePs_SWP_DFE)

## 🔋 Features

- 🔗 **URL Shortening** – Generate short, unique URLs for long links.
- 🌐 **Custom Short URLs** – Create personalized short URLs.
- 🔐 **User Authentication** – Secure login and registration using JWT.
- 📊 **Analytics** – Track URL visits and generate usage reports.

## ⚙️ Tech Stack

- **🎨 Frontend**: React, Redux, Tailwind CSS, Tanstack Router, Tanstack Query
- **🚀 Backend**: Node.js, Express.js (RESTful API)
- **🗄 Database**: MongoDB with Mongoose

## 🤸 Installation

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn
- MongoDB Atlas account (or local MongoDB instance)

### Setup

1. **Clone the repository**

   ```bash
   git clone https://github.com/soumadip-dev/URL-Shortener.git
   cd URL-Shortener
   ```

2. **Backend Setup**

   ```bash
   cd server
   npm install
   ```

   Create a `.env` file in the `server` directory with:

   ```env
   PORT=8080
   NODE_ENV=development
   MONGODB_URI=<YOUR_MONGODB_URI>
   APP_URL=http://localhost:8080
   JWT_SECRET=<YOUR_JWT_SECRET>
   ```

3. **Frontend Setup**

   ```bash
   cd ../client
   npm install
   ```

   Create a `.env` file in the `client` directory with:

   ```env
   VITE_BACKEND_URL=<YOUR_BACKEND_URL>
   ```

4. **Run the Application**
   - Backend (Terminal 1):
     ```bash
     cd server
     npm run dev
     ```
   - Frontend (Terminal 2):
     ```bash
     cd ../client
     npm run dev
     ```
