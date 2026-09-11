# 🎬 Nox Films

> A modern movie discovery and rating platform built entirely with React.js.

**Nox Films** is a modern movie discovery platform inspired by IMDb, but designed with a cleaner, more contemporary interface and a stronger focus on user experience.

The platform lets users explore movies, discover new titles, browse genres, view ratings and movie information, and navigate through a modern responsive interface.

> **Nox Films is a movie discovery and information platform. It does not host, upload, or distribute copyrighted movies.**

---

## ✨ Features

* 🎬 Modern movie discovery experience
* ⭐ Movie ratings and scores
* 🎭 Browse movies by genre
* 🔎 Search for movies
* 📄 Detailed movie information
* 🖼️ Movie posters and artwork
* 📱 Fully responsive design
* ⚡ Fast client-side experience
* 🧩 Reusable React components
* 📦 JSON-based movie database
* 🎨 Modern UI inspired by contemporary streaming platforms
* 🧭 Smooth navigation between movie categories and pages

---

## 🛠️ Tech Stack

### Frontend

* **React.js**
* **JavaScript**
* **HTML5**
* **CSS3**

### Data

The application currently uses local **JSON files** as its data source.

```text
JSON
 ↓
React
 ↓
Components
 ↓
UI
```

This makes the project simple to develop and easy to expand later with a real backend or external movie API.

---

## 📁 Project Structure

```text
Nox-Films/
│
├── public/
│   └── assets/
│
├── src/
│   │
│   ├── components/
│   │   ├── Navbar/
│   │   ├── MovieCard/
│   │   ├── MovieGrid/
│   │   ├── Rating/
│   │   └── Footer/
│   │
│   ├── pages/
│   │   ├── Home/
│   │   ├── Movies/
│   │   ├── Genres/
│   │   ├── MovieDetails/
│   │   └── Search/
│   │
│   ├── data/
│   │   └── movies.json
│   │
│   ├── assets/
│   │
│   ├── App.jsx
│   └── main.jsx
│
├── package.json
└── README.md
```

---

## 🎯 Main Goal

The goal of Nox Films is to build a modern movie platform that focuses on **discovery, information, and user experience**.

Instead of trying to recreate IMDb exactly, Nox Films takes inspiration from existing movie databases while creating its own visual identity and interface.

---

## 🗃️ Data Architecture

For the current version, movie information is stored locally inside JSON files.

Example:

```json
{
  "id": 1,
  "title": "Movie Title",
  "year": 2026,
  "rating": 8.7,
  "genre": ["Action", "Drama"],
  "duration": "2h 15m",
  "description": "Movie description...",
  "poster": "/assets/poster.jpg"
}
```

React consumes this data and renders the appropriate UI components dynamically.

This approach keeps the project lightweight while demonstrating how a frontend application can work with structured data.

---

## 🚀 Future Improvements

Nox Films is designed so the local JSON architecture can eventually be replaced with a real backend or external API.

Possible future features include:

* 🔐 User authentication
* 👤 User profiles
* ⭐ User reviews
* ❤️ Watchlist
* 🎯 Personalized recommendations
* 📊 Movie statistics
* 🔥 Trending movies
* 🎬 Actor and director pages
* 🌐 Real movie API integration
* 🗄️ Backend database
* ⚙️ Admin dashboard
* 🌙 Advanced theme system

---

## 📱 Responsive Design

Nox Films is designed to provide a consistent experience across:

* 🖥️ Desktop
* 💻 Laptop
* 📱 Mobile
* 📲 Tablet

The interface is built with responsive layouts rather than relying on a fixed desktop design.

---

## ⚡ Performance

Because the current version is entirely frontend-based and uses local JSON data, Nox Films can provide a fast browsing experience without depending on a backend server for every movie request.

---

## 📸 Screenshots

> Screenshots will be added here as the project UI evolves.

---

## 🧑‍💻 Development

Clone the repository:

```bash
git clone https://github.com/your-username/nox-films.git
```

Navigate to the project:

```bash
cd nox-films
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

---

## ⚖️ Disclaimer

Nox Films is an educational and portfolio project focused on frontend development, movie discovery, and user interface design.

The project does **not** host, upload, or distribute copyrighted movies.

Movie titles, images, descriptions, ratings, and other third-party data may belong to their respective owners.

Nox Films does not claim ownership of third-party movie content.

---

## 👨‍💻 Author

Built with ❤️ using React.js.

**Nox Films — Discover. Explore. Rate.**
