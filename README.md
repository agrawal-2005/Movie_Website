# Movie Website

A React-based web application for searching and displaying information about movies using the OMDB API.

## Table of Contents

- [Project Description](#project-description)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [API](#api)
- [Components](#components)
- [Contributing](#contributing)

## Project Description

Movie Website is a web application built with React that allows users to search for movies and view details about them. It fetches data from the OMDB (Open Movie Database) API and displays it in an organized manner. The app includes a search functionality and dynamic rendering of movie information.

## Features

- Search for movies by title.
- Display movie details including title, year, type, and poster.
- Responsive design that works on various screen sizes.
- Uses React hooks for managing state and effects.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/movie-website.git
    cd movie-website
    ```

2. Install the dependencies:
    ```bash
    npm install
    ```

3. Start the development server:
    ```bash
    npm start
    ```

4. Open your browser and go to `http://localhost:3000`.

## Usage

- On the homepage, you can use the search bar to search for movies.
- Enter a movie title and click the search icon to fetch results from the OMDB API.
- Movie results will be displayed below the search bar.

## API

This project uses the [OMDB API](http://www.omdbapi.com/) to fetch movie data. You need an API key to access the OMDB API. Replace the `API_URL` in the project with your own API key:

```javascript
const API_URL = "http://www.omdbapi.com?apikey=your_api_key";
```

## Components

### App.js

- Main component that includes the search functionality and displays movie results.
- Uses `useEffect` to fetch initial data and `useState` to manage state.

### MovieCard.js

- A functional component that displays individual movie details.
- Props: `movie` object containing title, year, type, and poster URL.

### App.css

- Contains styling for the application.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.