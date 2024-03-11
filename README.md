# 🍿 usePopcorn

usePopcorn is a react application that provides users with a way to explore movies, rate them, and manage their watched movies list. By leveraging the OMDB API (Open Movie Database), the app gains access to an extensive movie database, allowing users to quickly and easily find movie information, including genre, cast, director, ratings, and much more.

## Stack

- React: A JavaScript library for building user interfaces. It's the foundation of your application, enabling you to build your UI with components.
- Create React App (CRA): A boilerplate and toolchain for React applications. It sets up your development environment so you can use the latest JavaScript features, provides a nice developer experience, and optimizes your app for production.
- Open Movie Database (OMDb) API: A RESTful web service to obtain movie information. You'll be making HTTP requests to this API to fetch data based on user queries or other interactions.
- Node.js: Required to run JavaScript code on the server-side, primarily used here to run the development server and build tools provided by CRA.
  npm: Package manager for installing and managing project's dependencies.

## Features

- search movie
- show movie details
- rate movie and add to watched
- remove movie from watched
- show stats about your watched movies
- use Enter key to start searching movie
- use Esc key to close the movie detail
- watched movies stored in browser local storage

## Demo

![usePopcorn Demo](https://i.imgur.com/sRyo6B4.gif)
