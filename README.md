<h1 align="center">Anime Universe</h1>
<p align="center">
<img src="https://socialify.git.ci/MostafaSensei106/Mostafa-Mahmoud-Week2-Anime-Mini-App-Clean-Arch/image?custom_language=Flutter&font=KoHo&language=1&logo=https%3A%2F%2Favatars.githubusercontent.com%2Fu%2F138288138%3Fv%3D4&name=1&owner=1&pattern=Floating+Cogs&theme=Light" alt="Anime Universe Logo">
</p>

<p align="center">
<strong>A modern, feature-rich Anime mobile app built with Flutter for an immersive viewing experience.</strong>



</p>

<p align="center">
<a href="#about">About</a> •
<a href="#features">Features</a> •
<a href="#installation">Installation</a> •
<a href="#architecture">Architecture</a> •
<a href="#technologies">Technologies</a> •
<a href="#contributing">Contributing</a> •
<a href="#license">License</a>
</p>
About

Welcome to Anime Universe — a sleek and modern mobile application for anime enthusiasts. Built with Flutter, this app provides a beautiful interface to browse, discover, and track your favorite anime series and characters. Dive into a world "Where Anime Comes Alive" with stunning visuals, detailed information, and a seamless user experience designed for fans, by fans.
Features
🌟 Core Functionality

    Dynamic Home Page: Discover new, popular, and trending anime at a glance.

    Anime & Character Browsing: Scroll through extensive lists of anime posters and top characters.

    Detailed Views: Tap on any anime to see a rich details screen with genre tags, viewer stats (views, likes), and a full synopsis.

    Subscription Model: An integrated "Upgrade Plan" screen offers monthly and yearly subscriptions for a premium, ad-free experience.

    Intuitive Navigation: A custom-animated bottom navigation bar makes moving through the app effortless.

🎨 Modern UI/UX

    Gradient Backgrounds: Beautifully designed screens with subtle gradient effects and background assets.

    Responsive Design: Built with flutter_screenutil to ensure a consistent and pixel-perfect UI across various device sizes.

    Custom Widgets: Features custom-built cards for anime posters, characters, and subscription plans for a unique look and feel.

    Smooth Animations: Engaging transitions and micro-interactions provide a delightful user experience.

📱 Application UI

The application features three main screens:

    Home View: The main dashboard where users can browse lists of anime and top characters. It includes a horizontal tab bar for filtering content by categories like 'Popular', 'Trending', and 'Top Rated'.

    Anime Details View: A detailed screen that appears when an anime is selected. It showcases the anime's poster art, genre, stats, a brief description, and options to preview or watch.

    Upgrade Plan View: A dedicated screen for handling in-app subscriptions. It presents different pricing plans in a clean, user-friendly layout to encourage users to subscribe for premium features.

Installation
📦 Quick Setup

    [!IMPORTANT]
    A recent version of the Flutter SDK is required.
    Android Studio or VS Code with Flutter extensions recommended.

🛠️ Prerequisites

Before you begin, ensure you have:

    Flutter SDK

    Android Studio or VS Code

    Git installed on your system

📱 Running the App

# Clone the repository
git clone [https://github.com/your-username/anime-universe.git](https://github.com/your-username/anime-universe.git)

cd anime-universe

# Install dependencies
flutter pub get

# Run on connected device or emulator
flutter run

Architecture

Anime Universe is structured using a feature-first approach, with a clear separation of concerns between UI (views/widgets) and data (models).
🏗️ Project Structure

lib/
├── features/
│   ├── home/
│   │   ├── view/
│   │   │   ├── home_view.dart
│   │   │   └── widgets/
│   │   │       ├── anime_poster_card.dart
│   │   │       ├── character_card.dart
│   │   │       └── custom_bottom_nav_bar.dart
│   │   └── data/
│   │       └── models/
│   │           ├── anime_model.dart
│   │           └── character_model.dart
│   ├── anime_details/
│   │   └── view/
│   │       └── anime_details_view.dart
│   └── upgrade_plan/
│       └── view/
│           ├── upgrade_plan_view.dart
│           └── widgets/
│               └── subscription_plan_card.dart
└── core/
    ├── thmems/       # (Themes) App colors and text styles
    └── widgets/      # Shared widgets like GradientScaffold

🧩 Key Components

    Models: Plain Dart objects like AnimeModel and CharacterModel that define the data structure.

    Views: Screens such as HomeView and AnimeDetailsView that are responsible for displaying the UI.

    Widgets: Reusable UI components like AnimePosterCard and SubscriptionPlanCard that encapsulate specific parts of the UI. This modular approach makes the codebase easy to maintain and scale.

Technologies

Technology


Description


Purpose

🎯 Flutter


flutter.dev


Cross-platform UI framework

📱 Dart


dart.dev


Programming language

📏 flutter_screenutil


pub.dev/packages/flutter_screenutil


For adapting UI to different screen sizes

🎨 Material Design


material.io


UI components and design guidelines
Development
🔧 Code Quality

# Format code
flutter format .

# Analyze code
flutter analyze

# Check for outdated dependencies
flutter pub outdated

📱 Building for Production

# Build Android APK
flutter build apk --release

# Build iOS App Bundle
flutter build ipa --release

Contributing

Contributions are welcome! Here's how to get started:

    Fork the repository

    Create a feature branch:

    git checkout -b feature/amazing-feature

    Commit your changes:

    git commit -m "Add amazing feature"

    Push to your branch:

    git push origin feature/amazing-feature

    Open a pull request

📝 Contribution Guidelines

    Follow Flutter's official style guide.

    Write clean, readable, and well-documented code.

    Ensure the app runs without errors after making changes.

    Use conventional commit messages.

    💡 Please open an issue first for major feature ideas or architectural changes.

License

This project is licensed under the MIT License.
See the LICENSE file for full details.

<p align="center">
Made with ❤️
by <a href="https://github.com/MostafaSensei106">Mostafa Sensei106</a>
</p>
