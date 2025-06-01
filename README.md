# WordCrafter

WordCrafter is a Flutter app that generates random English word pairs, lets you favorite them, and view your favorites. It has a responsive UI for both mobile and desktop, and uses Provider for state management.

---

## Features

* Generate random English word pairs
* Mark word pairs as favorites
* View and remove favorites
* Animated history of generated word pairs
* Responsive layout for mobile (BottomNavigationBar) and desktop (NavigationRail)
* Built using Flutter, Provider, and the `english_words` package

---

## Screenshots

1. **Generator Page**
   ![Generator Page](https://github.com/shubhankar05sarkar/WordCrafter/blob/aab63167b1b460c430f01fdb8b98dbfc90be62f2/Generator%20Page.png)

   Generates random English word pairs. You can add any word pair to your favorites.

2. **Favorites Page**
   ![Favorites Page](https://github.com/shubhankar05sarkar/WordCrafter/blob/aab63167b1b460c430f01fdb8b98dbfc90be62f2/Favourites%20Page.png)

   Displays the word pairs you added to your favorites, with an option to delete any of them.

---

### Prerequisites

* [Flutter SDK](https://flutter.dev/docs/get-started/install)
* Dart
* Any IDE like Android Studio or VS Code

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/wordcrafter.git
   cd wordcrafter
   ```

2. Install dependencies:

   ```bash
   flutter pub get
   ```

3. Run the app:

   ```bash
   flutter run
   ```

---

## Project Structure

* **lib/main.dart**: Contains the main application code, UI, and state management.

  * Uses `provider` for state management.
  * Uses `english_words` for generating word pairs.

---

## Dependencies

* Flutter
* Provider
* english\_words

---

## How It Works

1. The app displays a random word pair on the home screen.
2. Tap **Like** to save the word pair to your favorites.
3. Tap **Next** to generate a new word pair.
4. Check the **Favorites** tab to view saved word pairs.
5. Remove a word pair from favorites by tapping the delete icon.
6. The app uses a bottom navigation bar for mobile and a navigation rail for desktop.

---

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

---

## **Author**

Created with ❤️ by **Shubhankar Sarkar**.  
[GitHub Profile](https://github.com/shubhankar05sarkar)

---
