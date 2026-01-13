# movies-happiness
This app showcases movies from the TMDB API while leveraging the power of modern Android development with Jetpack Compose and other cutting-edge libraries. 🚀
💡 Technologies Used:
⚛️ Jetpack Compose – Modern UI Toolkit
🎬 TMDB API – Fetch the latest movies, genres, and more!
🔗 Retrofit – For seamless network calls
🏛️ MVVM Architecture – Clean, maintainable code structure
🛡️ Hilt – Efficient dependency injection
📜 Paging 3 – Effortless pagination for movie listings
💾 Room Database – Save and manage your Wishlist
🧭 Navigation Compose – Smooth navigation experience
How It Works 💻
Home Screen: The app starts with an automatic sliding banner featuring the latest movies. Below that, it shows a genres listing, followed by multiple movie sections like "Now Playing", "Popular Movies", "Discover", and "Upcoming Movies".
Genres Listing: Each genre features a scrollable list of movies displayed using LazyColumn and Paging 3 for seamless pagination.
Movie Details: Click on a movie to see details like its name, description, language, rating, and more. You’ll also see related movies in the same genre.
Search: Use the search option to find any movie directly from the server.
Wishlist: Add your favorite movies to the wishlist using Room Database and swipe to remove them easily.
Libraries Used 📚
Jetpack Compose: Modern UI toolkit for building native Android UIs.
TMDB API: Provides access to movies, TV shows, and cast information.
Retrofit: Type-safe HTTP client for Android and Java.
MVVM Architecture: Separates UI, business logic, and data management for easy maintainability.
Dagger-Hilt: Reduces the boilerplate of manual dependency injection.
Paging 3: Handles large data sets by loading content in chunks.
Room Database: Local persistence for saving favorite movies.
Navigation Compose: Handles app navigation in a declarative way.
