# News Outlet App

A modern Android application for browsing and reading news articles with a beautiful user interface.

## Features

- Browse news articles in a modern, card-based interface
- Folding cell animations for article previews
- Smooth scrolling and responsive UI
- Image loading and caching with Picasso
- Web view integration for reading full articles
- Network requests handling with Volley
- Real-time news updates from TheNewsAPI

## API Integration

This app uses [TheNewsAPI](https://www.thenewsapi.com/) to fetch news articles. TheNewsAPI provides:
- Access to news from over 40,000 sources
- Coverage across 50+ countries
- Support for 30+ languages
- Real-time news updates
- Advanced search and filtering capabilities

## Technical Details

- Minimum SDK: 19 (Android 4.4)
- Target SDK: 29 (Android 10)
- Built with AndroidX libraries
- Uses Gradle for build management

## Dependencies

- AndroidX AppCompat
- AndroidX ConstraintLayout
- AndroidX RecyclerView
- AndroidX CardView
- Ramotion Folding Cell
- Picasso for image loading
- Volley for networking
- FinestWebView for article viewing

## Building the Project

1. Clone the repository
2. Open the project in Android Studio
3. Sync Gradle files
4. Build and run the application

## Development

The project uses standard Android development practices and follows Material Design guidelines. The main components are:

- RecyclerView for displaying news articles
- Folding Cell for article previews
- CardView for article cards
- WebView for reading full articles
