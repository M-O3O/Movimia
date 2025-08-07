# Movie App

A modern web application for discovering, searching, and exploring movies. Built with React and Vite, this app provides a fast and interactive user experience.

## Features

- **Movie Search:**
  - Search for movies by title using a responsive search bar.
  - Instant search results as you type.

- **Movie Listings:**
  - Browse a curated list of movies with posters, titles, and ratings.
  - View detailed information for each movie, including synopsis, release year, and rating.

- **Responsive Design:**
  - Fully responsive layout for mobile, tablet, and desktop devices.

- **Loading Spinner:**
  - Displays a spinner while fetching data to enhance user experience.

- **No Results Handling:**
  - Friendly message and image when no movies are found for a search query.

- **Attractive UI:**
  - Modern and clean interface with custom assets and icons.

## How It Works

1. **Search:** Enter a movie name in the search bar to find movies instantly.
2. **Browse:** Scroll through the list of movies and click on any card to view more details.
3. **Details:** See movie posters, ratings, and additional information for each movie.

## Getting Started

1. Install dependencies:
   ```bash
   npm install
   # or
   bun install
   ```
2. Start the development server:
   ```bash
   npm run dev
   # or
   bun run dev
   ```
3. Open your browser at `http://localhost:5173` (or the port shown in your terminal).

## Technologies Used
- React
- Vite
- CSS Modules
- Appwrite (for backend, if configured)

## Folder Structure
- `src/components/` – UI components (MovieCard, Search, Spinner)
- `public/` – Static assets and images
- `src/App.jsx` – Main app logic

## Customization
- Update assets in the `public/` folder for branding.
- Modify styles in `src/App.css` and `src/index.css`.

---

Feel free to contribute or customize this app for your own movie discovery experience!