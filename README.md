# Movie Search App

## Overview

The Movie Search App, known as **kinoLab**, is a web application that allows users to search for movies and view detailed information about them. It provides access to a vast database of movies and enables users to keep track of movies they've watched and rate them.

## Features

- **Movie Search**: Easily search for movies by typing in keywords in the search bar.

- **Movie Details**: Click on a movie from the search results to view detailed information about it, including its title, release date, genre, IMDb rating, and more.

- **Add to Watched List**: Rate and add movies you've watched to your personal "Watched" list. You can also delete movies from this list.

- **Average Ratings**: Get statistics on the movies you've watched, including the average IMDb and user ratings, as well as the average runtime.

## Technologies Used

- **React**: The app is built using React, a popular JavaScript library for building user interfaces.

- **OMDb API**: The app fetches movie data from the OMDb API, which provides comprehensive information about movies.

- **LocalStorage**: The app uses browser local storage to persist the "Watched" list, ensuring that your watched movies are saved even after closing the app.

- **Custom Hooks**: Custom hooks like `useMovies`, `useLocalStorageState`, and `useKey` are used to manage specific functionalities efficiently.

## Usage

- Enter keywords in the search bar to search for movies.

- Click on a movie from the search results to view its details.

- Rate and add movies you've watched to the "Watched" list.

- Delete movies from the "Watched" list by clicking the delete button.

- View average ratings and statistics about your watched movies in the "Watched Summary" section.
