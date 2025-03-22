# Flutter API ListView

## Description
A simple Flutter application that fetches data from a public API and displays post titles in a scrollable ListView. The app includes error handling and a loading indicator.

## Features
- Fetches data from `https://jsonplaceholder.typicode.com/posts`
- Displays post titles and body in a `ListView`
- Shows a `CircularProgressIndicator` while fetching data
- Handles errors gracefully with an error message
- Includes a pull-to-refresh feature using `RefreshIndicator`

## Requirements
- Flutter SDK
- Dart
- `http` package for API requests

## Setup Instructions
1. Clone this repository:
   ```sh
   git clone https://github.com/your-repo/flutter-api-listview.git
   cd flutter-api-listview
   ```
2. Install dependencies:
   ```sh
   flutter pub get
   ```
3. Run the app:
   ```sh
   flutter run
   ```

## Assumptions
- The API endpoint always returns valid JSON data.
- No authentication is required for API access.

## Additional Enhancements
- Pull-to-refresh feature to reload data
- Clean and structured code following Flutter best practices

