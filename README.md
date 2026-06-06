# BlogHub 📝
### *A new way to share stories.*

BlogHub is a full-stack blogging platform where anyone can write and discover content across multiple domains — from healthcare and career advice to lifestyle, fashion, and beyond. Think of it as your personal publishing space, combined with a community feed of ideas from people who actually care about what they write.

---

## 🌟 Why BlogHub?

Most people have something worth saying. The problem is — where do you say it?

Social media is noisy. Medium has a paywall. LinkedIn is too formal. Personal blogs get zero readers.

BlogHub fixes that. It gives you a clean space to write, organize your blogs by category, and share them with people who are actually interested in that topic. Whether you're a healthcare professional sharing tips or a fashion enthusiast writing style guides — there's a place for you here.

---

## ✨ Features

- 📚 **Multi-Category Blogging** — Post blogs across Healthcare, Lifestyle, Fashion, Career, Technology, and more
- 🖊️ **Rich Text Editor** — Write and format your posts easily
- 👤 **User Authentication** — Secure signup/login with JWT
- 🗂️ **Category-Based Feed** — Browse posts by the topics you care about
- 💬 **Author Profiles** — Every writer gets their own public page
- 🔍 **Search & Filter** — Find blogs by category or keyword
- 📱 **Responsive Design** — Works on any device, any screen size

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|------------|
| **Frontend** | React.js |
| **Backend** | Node.js + Express.js |
| **Database** | MongoDB (with Mongoose) |
| **Auth** | JWT (JSON Web Tokens) |
| **Styling** | CSS / Tailwind CSS |
| **API** | RESTful API |

**Stack: MERN (MongoDB, Express, React, Node)**

---

## 🎬 Demo

> 📺 **[Watch the Demo Video](#)** — A 2-minute walkthrough of the full app

*(Demo video coming soon — screen recording of key features)*

---

## 🚀 Getting Started

Want to run this locally? Here's how:

### Prerequisites
Make sure you have these installed:
- Node.js (v14 or higher)
- MongoDB (local or MongoDB Atlas)
- npm or yarn

### Installation

```bash
# 1. Clone the repo
git clone https://github.com/your-username/bloghub.git
cd bloghub

# 2. Install backend dependencies
cd server
npm install

# 3. Install frontend dependencies
cd ../client
npm install
```

### Environment Variables

Create a `.env` file in the `/server` folder:

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
PORT=5000
```

### Run the App

```bash
# Start the backend (from /server)
npm run dev

# Start the frontend (from /client)
npm start
```

Open your browser and go to `http://localhost:3000` — you're in!

---

## 📁 Project Structure

```
bloghub/
├── client/                  # React frontend
│   ├── src/
│   │   ├── components/      # Reusable UI components
│   │   ├── pages/           # Route-level pages
│   │   ├── context/         # Auth context
│   │   └── App.js
├── server/                  # Node.js + Express backend
│   ├── models/              # Mongoose schemas
│   ├── routes/              # API routes
│   ├── middleware/          # Auth middleware
│   └── server.js
└── README.md
```

---

## 📌 API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | `/api/auth/register` | Create new account |
| POST | `/api/auth/login` | Login and get token |
| GET | `/api/blogs` | Get all blogs |
| GET | `/api/blogs/:id` | Get single blog |
| POST | `/api/blogs` | Create new blog (auth required) |
| PUT | `/api/blogs/:id` | Update blog (auth required) |
| DELETE | `/api/blogs/:id` | Delete blog (auth required) |
| GET | `/api/blogs/category/:name` | Get blogs by category |

---

## 🔮 What's Next (Planned Features)

- [ ] Like and comment system
- [ ] Follow authors
- [ ] Email newsletter for new posts
- [ ] Dark mode
- [ ] Deploy on Vercel + Render

---

## 🤝 Contributing

Got an idea or found a bug? Contributions are welcome!

1. Fork the repo
2. Create a branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add your feature'`)
4. Push and open a Pull Request

---


## 👤 About the Developer

Built with ❤️ by **Kanchan Borole**

- GitHub: [KanchanBorole](https://github.com/KanchanBorole)
- LinkedIn: [kanchan-borole](https://linkedin.com/in/kanchan-borole)

---

> *"Everyone has a story worth telling. BlogHub just gives you the space to tell it."*
