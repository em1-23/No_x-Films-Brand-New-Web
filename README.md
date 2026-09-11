# 🎬 Nox Films

### A modern movie discovery platform built with React.js

<p align="center">
  <strong>Discover movies. Explore stories. Find your next favorite.</strong>
</p>

<p align="center">
  <a href="#-features">Features</a>
  •
  <a href="#-tech-stack">Tech Stack</a>
  •
  <a href="#-architecture">Architecture</a>
  •
  <a href="#-getting-started">Getting Started</a>
  •
  <a href="#-roadmap">Roadmap</a>
</p>

---

## 📖 About

**Nox Films** is a modern movie discovery and information platform inspired by the concept of IMDb, redesigned with a cleaner interface, modern interactions, and a more cinematic user experience.

The application allows users to discover movies, explore genres, search for titles, view detailed movie information, and browse ratings through a fully responsive React.js interface.

Nox Films is intentionally designed as a **frontend-focused project**, with movie data currently provided through structured JSON files.

> 🎯 **Project Focus:** React architecture, reusable components, responsive UI, data-driven rendering, search, filtering, and modern frontend development.

---

## ✨ Features

### 🎬 Movie Discovery

* Browse a collection of movies
* Featured movie sections
* Popular and recommended categories
* Genre-based browsing
* Movie cards with dynamic information

### 🔎 Search & Filtering

* Search movies by title
* Filter movies by genre
* Browse categorized movie collections
* Dynamic results powered by JSON data

### ⭐ Movie Information

* Movie ratings
* Release year
* Genres
* Runtime
* Description
* Poster artwork
* Additional movie metadata

### 🎨 Modern UI

* Cinematic visual style
* Responsive layouts
* Modern movie cards
* Clean navigation
* Reusable UI components
* Mobile-friendly experience

### ⚡ Frontend Architecture

* Component-based React architecture
* Data-driven UI
* Reusable components
* Local JSON data layer
* Client-side rendering
* Scalable project structure

---

## 🖥️ Preview

> Screenshots will be added here.

```text
┌─────────────────────────────────────────────────────────────┐
│                         NOX FILMS                            │
│                                                             │
│              Discover Your Next Favorite Movie              │
│                                                             │
│        [ Search movies...                         🔍 ]       │
│                                                             │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│  Trending Now                                               │
│                                                             │
│  ┌────────┐  ┌────────┐  ┌────────┐  ┌────────┐            │
│  │ Movie  │  │ Movie  │  │ Movie  │  │ Movie  │            │
│  │  ★8.7  │  │  ★9.1  │  │  ★8.4  │  │  ★8.9  │            │
│  └────────┘  └────────┘  └────────┘  └────────┘            │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

---

# 🛠️ Tech Stack

| Technology     | Purpose                      |
| -------------- | ---------------------------- |
| **React.js**   | Frontend framework           |
| **JavaScript** | Application logic            |
| **HTML5**      | Semantic structure           |
| **CSS3**       | Styling & responsive layouts |
| **JSON**       | Movie data source            |
| **Git**        | Version control              |
| **GitHub**     | Source code & collaboration  |

---

# 🏗️ Architecture

Nox Films follows a simple data-driven frontend architecture.

```text
                     ┌──────────────────┐
                     │    JSON DATA     │
                     │                  │
                     │    movies.json   │
                     └────────┬─────────┘
                              │
                              ▼
                     ┌──────────────────┐
                     │   React Logic    │
                     │                  │
                     │ Search / Filter  │
                     │   Data Mapping   │
                     └────────┬─────────┘
                              │
                              ▼
                  ┌───────────────────────┐
                  │   Reusable Components │
                  │                       │
                  │ MovieCard             │
                  │ MovieGrid             │
                  │ Navbar                │
                  │ Rating                │
                  │ Search                │
                  └───────────┬───────────┘
                              │
                              ▼
                     ┌──────────────────┐
                     │        UI        │
                     │                  │
                     │ Desktop / Tablet │
                     │      / Mobile    │
                     └──────────────────┘
```

The architecture keeps the data layer separated from the UI, making it easier to replace the JSON source with an API or backend in the future.

---

# 📂 Project Structure

```text
nox-films/
│
├── public/
│   └── assets/
│       ├── posters/
│       └── images/
│
├── src/
│   │
│   ├── components/
│   │   ├── Navbar/
│   │   ├── MovieCard/
│   │   ├── MovieGrid/
│   │   ├── SearchBar/
│   │   ├── Rating/
│   │   └── Footer/
│   │
│   ├── pages/
│   │   ├── Home/
│   │   ├── Movies/
│   │   ├── Genres/
│   │   ├── Search/
│   │   └── MovieDetails/
│   │
│   ├── data/
│   │   └── movies.json
│   │
│   ├── assets/
│   │
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
│
├── package.json
├── README.md
└── .gitignore
```

---

# 🗃️ Data Structure

Movies are currently represented using structured JSON objects.

```json
{
  "id": 1,
  "title": "Movie Title",
  "year": 2026,
  "rating": 8.7,
  "genres": [
    "Action",
    "Drama"
  ],
  "runtime": "2h 15m",
  "description": "Movie description...",
  "poster": "/assets/posters/movie.jpg"
}
```

React uses this structured data to dynamically generate movie cards, search results, details pages, and category sections.

---

# 🔄 Data Flow

```text
movies.json
     │
     ▼
React Application
     │
     ├── Search
     │
     ├── Filtering
     │
     ├── Sorting
     │
     └── Categorization
     │
     ▼
Reusable Components
     │
     ▼
Rendered UI
```

This approach makes the frontend independent from hardcoded UI content and allows the application to scale as the movie dataset grows.

---

# 📱 Responsive Design

Nox Films is designed to work across different screen sizes:

* 🖥️ Desktop
* 💻 Laptop
* 📱 Mobile
* 📲 Tablet

The interface adapts its layout, spacing, typography, and movie grids depending on the available screen size.

---

# ⚡ Performance

The current version uses local JSON data instead of making network requests for every movie interaction.

This provides:

* Fast initial interactions
* Simple data access
* No backend dependency
* Easy local development
* Predictable frontend behavior

The architecture is also designed so that the local data source can later be replaced with a real API.

---

# 🚀 Getting Started

## 1. Clone the repository

```bash
git clone https://github.com/your-username/nox-films.git
```

## 2. Navigate into the project

```bash
cd nox-films
```

## 3. Install dependencies

```bash
npm install
```

## 4. Start the development server

```bash
npm run dev
```

The application will be available through the local development URL provided by Vite.

---

# 🧪 Development Goals

Nox Films was created to demonstrate practical frontend development concepts such as:

* React component architecture
* Props and reusable components
* State management
* Dynamic rendering
* Array manipulation
* Search functionality
* Filtering
* Responsive CSS
* Structured local data
* UI/UX implementation
* Project organization

---

# 🗺️ Roadmap

### ✅ Phase 1 — Core Platform

* [x] React application
* [x] Movie dataset
* [x] Movie cards
* [x] Responsive layout
* [x] Movie information
* [x] Genre system

### 🚧 Phase 2 — Discovery

* [ ] Advanced search
* [ ] Advanced filtering
* [ ] Sorting
* [ ] Trending section
* [ ] Better recommendations
* [ ] Improved movie details

### 🔮 Phase 3 — User Experience

* [ ] Watchlist
* [ ] User ratings
* [ ] Reviews
* [ ] User profiles
* [ ] Personalized recommendations
* [ ] Recently viewed movies

### 🌐 Phase 4 — Backend

* [ ] REST API
* [ ] Database
* [ ] Authentication
* [ ] User management
* [ ] Admin dashboard
* [ ] External movie API integration

---

# 🔌 Future Architecture

The current architecture:

```text
React
  │
  └── JSON
```

Can later evolve into:

```text
                    ┌──────────────┐
                    │    React     │
                    │   Frontend   │
                    └──────┬───────┘
                           │
                         REST
                           │
                           ▼
                    ┌──────────────┐
                    │   Backend    │
                    │     API      │
                    └──────┬───────┘
                           │
                           ▼
                    ┌──────────────┐
                    │   Database   │
                    └──────────────┘
```

This allows Nox Films to grow from a frontend project into a complete full-stack movie platform.

---

# 🎯 Why Nox Films?

Nox Films is more than a movie catalog.

The project is designed to demonstrate how a real-world frontend application can take structured data and transform it into a polished, interactive user experience.

The main focus is not simply displaying movies, but building a maintainable architecture that can evolve as the application grows.

---

# ⚖️ Disclaimer

Nox Films is an educational and portfolio project focused on **movie discovery, information, and frontend development**.

The platform does **not** host, upload, or distribute copyrighted movies.

Nox Films does not provide unauthorized movie streaming links or instructions for accessing copyrighted content.

Movie titles, artwork, descriptions, ratings, and other third-party information may belong to their respective copyright holders.

---

# 👨‍💻 Author

Built with ❤️ and React.js.

**Nox Films**

> Discover. Explore. Rate.

---

<p align="center">
  Made with React.js • Built for the web • Designed for movie lovers
</p>
