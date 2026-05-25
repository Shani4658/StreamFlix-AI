# 🎬 Streamflix-AI

Netflix-AI is a modern AI-powered movie recommendation and streaming UI application inspired by Netflix. The project integrates TMDB APIs for movie data and Google Gemini APIs for intelligent movie suggestions based on user prompts.

Built using React.js, Tailwind CSS, Firebase Authentication, Redux Toolkit, and Google Gemini APIs.

---
# 🌐 Live Demo

🚀 https://netflix-gpt-o9j6.vercel.app/browse

---

# 🚀 Deployment

The project is deployed using Vercel.

Supported deployment platforms:

- Vercel
- Netlify
- Render

# 🚀 Features

## 🔐 Authentication

* User Sign Up & Login
* Firebase Authentication
* Protected Browse Routes
* Sign Out Functionality
* User Profile Management
* Form Validation

## 🎥 Movie Browsing

* Fetches real-time movie data from TMDB API
* Now Playing Movies
* Popular Movies
* Trailer Playback
* Movie Suggestions
* Dynamic Movie Lists
* Responsive Netflix-style UI

## 🤖 GPT Movie Recommendation

* AI-powered movie recommendations
* Gemini AI-based search functionality
* Smart movie suggestions based on prompts
* Multi-language support

## 🎨 UI & UX

* Fully Responsive Design
* Modern Netflix-inspired interface
* Tailwind CSS styling
* Auto-playing YouTube trailers
* Smooth user experience

---

# 🛠️ Tech Stack

## Frontend

* React.js
* JavaScript
* Tailwind CSS
* Redux Toolkit
* React Router DOM

## Backend & APIs

* Firebase Authentication
* TMDB API
* Google Gemini API

## Deployment

* Firebase Hosting / Vercel / Netlify

---

# 📂 Project Structure

```bash
src/
│
├── components/
├── hooks/
├── utils/
├── store/
├── pages/
├── constants/
└── assets/
```

---

# ⚙️ Installation & Setup

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/Shani4658/netflix-gpt.git
cd netflix-gpt
```

---

## 2️⃣ Install Dependencies

```bash
npm install
```

---

## 3️⃣ Setup Firebase

1. Go to Firebase Console
2. Create a new project
3. Enable Authentication
4. Copy Firebase configuration
5. Add configuration to your project

---

## 4️⃣ Setup TMDB API

1. Visit TMDB website
2. Create an account
3. Generate API Access Token
4. Add token inside constants/config file

---

## 5️⃣ Setup Gemini API

1. Visit Google AI Studio
2. Generate Gemini API Key
3. Add API key to environment variables

Install OpenAI package:

```bash
npm install @google/generative-ai
```

---

# ▶️ Running the Project

## Start Development Server

```bash
npm start
```

Open:

```bash
http://localhost:3000
```

---

# 🧠 Application Flow

## Authentication Flow

* User Sign Up/Login
* Firebase verifies credentials
* Redirect to Browse Page
* Protected routes for authenticated users

## Browse Page

* Header Navigation
* Main Featured Movie
* Auto-playing Trailer
* Movie Categories
* Movie Cards
* Dynamic Suggestions

## AI Search Flow

1. User enters movie mood or prompt
2. Gemini AI processes the prompt
3. Suggested movie names are generated
4. TMDB fetches movie details
5. Movies are displayed dynamically

---

# 📸 Key Features Breakdown

## 🎞️ Main Container

* Featured movie banner
* Movie title and description
* Embedded YouTube trailer
* Auto-play and mute functionality

## 🎬 Secondary Container

* Multiple movie categories
* Horizontally scrollable movie lists
* Dynamic rendering using reusable components

## 🤖 AI Search Page

* Gemini AI-powered movie recommendations
* Search bar and suggestion system
* Multi-language search support

---

# 🔥 Custom Hooks Used

* `useNowPlayingMovies()`
* `usePopularMovies()`
* `useMovieTrailer()`
* `useMovieSuggestions()`

These hooks help in maintaining clean and reusable code.

---

# 🌍 Multi-Language Support

The project supports multiple languages for GPT search functionality and UI enhancement.

---

# 🧰 Redux Store

Redux Toolkit is used for:

* User Authentication State
* Movie Data Management
* Trailer Data
* AI Search Results
* Application State Handling

---

# 🎯 Future Improvements

* Add Watchlist Feature
* Add Movie Ratings & Reviews
* Add Voice-based AI Search
* Add User Recommendation History
* Add Dark/Light Theme Toggle
* Add Personalized AI Recommendations
* Add Streaming Platform Filtering

---

# 📦 Build for Production

```bash
npm run build
```

---

# 🚀 Deployment

The project can be deployed on:

* Vercel
* Netlify
* Firebase Hosting

---

# 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Push to your branch
5. Open a Pull Request

---

# 📄 License

This project is built for educational and learning purposes.

---

# 👨‍💻 Author

**Shani Dev Kashyap**

Frontend Developer | React.js Enthusiast | AI & Web Development Learner

---

# ⭐ Support

If you liked this project, give it a ⭐ on GitHub.
