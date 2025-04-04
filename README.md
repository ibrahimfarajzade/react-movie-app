# React Movie App

A simple movie search and discovery app built with React and The Movie Database (TMDB) API.

## Features

- Search for movies using The Movie Database API.
- Display trending movies based on popularity.
- Debounced search to optimize API calls.
- Responsive UI with movie details such as title, rating, release date, and language.
- Error handling and loading state for better user experience.

## Technologies Used

- **React** – Frontend framework
- **TypeScript** – Type safety
- **Fetch API** – For API requests
- **useState & useEffect** – State and side effect management
- **react-use (useDebounce)** – Debounced search input handling
- **Tailwind CSS** – Styling (if applicable)

## Setup Instructions

### Prerequisites

- [Node.js](https://nodejs.org/) installed
- TMDB API Key (Get yours at [TMDB](https://www.themoviedb.org/documentation/api))

### Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/yourusername/react-movie-app.git
   cd react-movie-app
   ```

2. Install dependencies:

   ```sh
   npm install
   ```

3. Create a `.env` file in the root directory and add:

   ```env
   VITE_TMDB_API_KEY=your_api_key_here
   ```

4. Start the development server:

   ```sh
   npm run dev
   ```

5. Open the app in your browser:

   ```
   http://localhost:5173
   ```

## API Usage

This app fetches movie data from [The Movie Database API](https://www.themoviedb.org/).

- **Search Movies:** `/search/movie?query=<movie_name>`
- **Discover Popular Movies:** `/discover/movie?sort_by=popularity.desc`

## License

This project is open-source and available under the [MIT License](LICENSE).

---
