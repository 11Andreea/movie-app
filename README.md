# 🎬 Movie App

A movie browsing application built with **React** as part of my learning journey.

The project uses a movie API to fetch and display movies, React Context for global state management, and Local Storage to persist the user's favorite movies.

> This project was built while following a tutorial and is mainly intended as a learning project.

## Features

- Browse movies fetched from an external API
- Search for movies
- Add and remove movies from favorites
- Dedicated Favorites page
- Favorites persist using Local Storage
- Global state management with React Context
- Responsive interface

## Technologies

- **React**
- **JavaScript**
- **CSS**
- **React Context API**
- **Local Storage**
- **REST API**
- **Vite**

## What I Learned

Through this project, I practiced:

- Working with APIs and asynchronous requests
- Fetching and displaying external data
- Managing global state with React Context
- Using React hooks
- Passing data between components
- Persisting data with Local Storage
- Creating reusable React components
- Structuring a React application
- Handling loading and error states

## Project Structure

```text
movie-app/
├── public/
├── src/
│   ├── components/
│   ├── contexts/
│   ├── pages/
│   ├── services/
│   ├── App.jsx
│   └── main.jsx
├── .gitignore
├── package.json
└── README.md
```

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/11Andreea/movie-app.git
cd movie-app
```

### 2. Install dependencies

```bash
npm install
```

### 3. Start the development server

```bash
npm run dev
```

The application will then be available at the local development URL provided by Vite.

## API

The application uses an external movie API to retrieve movie information.

## Favorites & Local Storage

The Favorites page uses **Local Storage** so that selected movies remain saved after refreshing or reopening the application.

The basic flow is:

```text
Movie
  ↓
Add to Favorites
  ↓
React Context
  ↓
Local Storage
  ↓
Favorites Page
```

## Screenshots

Screenshots will be added soon.

## Project Status

🟢 Completed as a learning project.

Possible future improvements:

- [ ] Add movie details pages
- [ ] Add review functionality
- [ ] Add movie status(watched, watching)
- [ ] Improve search functionality
- [ ] Add pagination
- [ ] Add sorting and filtering
- [ ] Improve accessibility
- [ ] Improve UI/UX
- [ ] Add more advanced error handling

## Purpose

This project was created to gain practical experience with **React, APIs, Context API, state management, and browser storage**.

It is part of my growing collection of projects while learning web development.
