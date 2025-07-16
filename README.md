# 📌 Link Saver + Auto-Summary

An intelligent and secure web application to **save, organize, and auto-summarize** your favorite web links. Built with a modular full-stack architecture for performance, maintainability, and a clean developer experience.

---

## 🚀 Features

### 🔐 Authentication

* Secure **JWT-based login & signup**
* Input validation and route protection

### 🔗 Link Management

* Save any valid URL
* Auto-summarization using **Cheerio** (or other NLP tools)
* Links displayed with title, description, and optional thumbnail

### 🧠 Auto Summary

* Extracts readable text content from web pages
* Summarizes articles using lightweight NLP or scraping logic

### 🌐 Frontend UI

* Modern, clean, and responsive design
* Optimized for desktop & mobile

### 🧱 Backend Structure

* Express.js server with modular routes, controllers, and middlewares
* MongoDB integration with Mongoose schemas
* Uses environment variables and `.env.example`

---

## 🏗️ Project Structure

```
link-saver-ui/
├── link-saver-backend/
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   ├── middleware/
│   ├── utils/
│   ├── config/
│   ├── .env.example
│   └── server.js
│
├── link-saver-frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   └── App.jsx
│   └── package.json
└── README.md
```

---

## 🛠️ Tech Stack

### 🔧 Backend:

* Node.js + Express.js
* MongoDB + Mongoose
* Cheerio (for content parsing)
* JWT for authentication

### 🎨 Frontend:

* React.js
* Tailwind CSS (or custom CSS)
* Axios for API communication

---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/NIKHILSONI9/link-saver-auto-summary.git
cd link-saver-ui
```

### 2. Backend Setup

```bash
cd link-saver-backend
cp .env.example .env
npm install
npm run dev
```

### 3. Frontend Setup

```bash
cd ../link-saver-frontend
npm install
npm run dev
```

> Make sure MongoDB is running locally or provide a cloud URI.

---

## 📚 Future Improvements

* Add user-based folder/tag system
* Integrate GPT or LLM for deep summaries
* Add preview images and metadata
* Export saved links to PDF or CSV

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change.

---

## 📄 License

This project is licensed under the MIT License.

---

## ✨ Acknowledgements

* [Cheerio](https://cheerio.js.org/)
* [MongoDB](https://www.mongodb.com/)
* [Express](https://expressjs.com/)
* [React](https://reactjs.org/)
