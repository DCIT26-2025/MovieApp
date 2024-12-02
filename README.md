# HomeScreen Component

This is a React Native component that displays a list of movies fetched from The Movie Database (TMDb) API. Users can search for movies and navigate to a details screen for each movie.

## Features

- Fetches and displays a list of popular movies from TMDb API.
- Infinite scrolling to load more movies as the user scrolls.
- Search functionality to filter movies by title.
- Navigation to a details screen for each movie.

## Installation

1. Clone the repository.
2. Install the dependencies using `npm` or `yarn`:

   ```bash
   npm install
   # or
   yarn install

   Ensure you have the necessary environment setup for React Native development.
Usage
Start the development server:

npm run android
# or
npm run ios


Code Overview
Dependencies
react
react-native
@react-navigation/native
@react-navigation/stack
@expo/vector-icons
lodash.debounce
Components
HomeScreen: The main component that fetches and displays the list of movies.
API Key
The API key for TMDb is hardcoded in the component. For production use, consider storing the API key securely.

Styles
The component uses StyleSheet from react-native to style the UI elements.

Navigation
The component uses useNavigation from @react-navigation/native to navigate to the details screen.

Functions
fetchMovies: Fetches movies from TMDb API.
loadMoreMovies: Loads more movies when the user scrolls to the end of the list.
navigateToDetails: Navigates to the details screen for a selected movie.
handleSearch: Handles the search input with debounce.

License
This project is licensed under the MIT License.

