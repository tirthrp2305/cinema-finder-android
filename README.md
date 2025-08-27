# cinema-finder-android
Android app to find nearby cinemas, search movies, and save favorites.
CinemaFinder is a native Android project that locates nearby cinemas and lets you search titles and save favorites. The code is organized with MVVM, ViewModel/LiveData (or Flow), Retrofit for REST, and Room for offline caching. The goal is to demonstrate clean architecture, testable data layers, and modern Android patterns.

Highlights to mention under About:

Location search: device location → nearby cinemas (FusedLocationProvider).

Movie lookup: Retrofit against TMDb/OMDb (API key kept out of VCS).

Persistence: Room favorites + simple offline cache.

Architecture: MVVM, Repository pattern, Kotlin coroutines, Material 3 UI.
