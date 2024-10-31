## Next.js Movie Search Challenge

This project is a Next.js application that fetches and displays a list of popular movies using The Movie Database (TMDb) API. The goal is to create a search bar with fuzzy matching and optimization features to enhance the user experience.

# Current Implementation
The app currently:

- Fetches a list of popular movies from the TMDb API and displays their titles on the homepage.
- Has a basic page structure set up with a list of movie titles in the <ul> element.
- The initial setup in pages/index.js does the following:
    - Connects to the TMDb API and retrieves popular movies on page load.
    - Renders the fetched movies in a simple list.

# Your Tasks
Please complete the following tasks to enhance the application:

1. Search Bar with Fuzzy Matching
    - Add a search bar at the top of the page to allow users to search for movies.
    - Implement fuzzy matching in the search so that users can find partial matches. For example, searching "Spid" should match "Spider-Man".
2. Debouncing
    - Implement debouncing on the search input to avoid frequent re-renders or excessive filtering as the user types. Aim for a delay of around 500ms.
3. Optional Enhancements
    - Add basic styling to the search bar and movie list to make the page more visually appealing.
    - If desired, organize your code with reusable components (e.g., SearchBar, MovieList).

# Running the Project
To start the development server:

´npm run dev´

