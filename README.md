# Penkit Pro


I created this web app in Flutter to have my information available across any platform: Windows, Linux, macOS, and the web. I'm planning to create pages and tool tours to easily access my scripts and commands at any time.

I also have a faster CLI version called [**Toda**](<https://github.com/4rji/Todo>), available on GitHub.

While I'm constantly improving this web version, it's more time-consuming to maintain, so **Toda** will have more up-to-date information.


## Description

Penkit Pro is a web application built with Flutter that utilizes CanvasKit for rendering. The application features a custom loading screen with percentage indicators and smooth transitions.

## Features

- Custom loading screen with percentage indicator
- CanvasKit/Skwasm rendering support
- Responsive web design
- Custom fonts including:
  - Press Start 2P
  - Lexie Readable
  - Material Icons


## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

# Flutter Project Setup (macOS)

## Requisitos previos

- Flutter instalado  
- Xcode instalado  
- Proyecto ya clonado localmente  

## Pasos para ejecutar el proyecto

1. Entrar al directorio del proyecto:
```bash
cd Penkit-Pro
```

3. Install dependencies:
```bash
flutter pub get
```

4. Run the application:
```bash
flutter run -d chrome
```

## Development Setup (macOS)

If you encounter CodeSign related issues, follow these steps:

1. Clean the project:
```bash
flutter clean
```

2. Remove extended attributes:
```bash
sudo xattr -cr .
```

3. If signing issues persist, open in Xcode:
```bash
open macos/Runner.xcworkspace
```
Then select a valid Team in the Signing & Capabilities tab.

## Building for Production

To build the application for production:

```bash
flutter build web
```

The built files will be available in the `build/web` directory.

## Tech Stack

- Flutter Web
- CanvasKit/Skwasm for rendering
- Service Worker for offline capabilities
- Custom web assets and fonts


## Resources

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)
- [Flutter documentation](https://docs.flutter.dev/)

## Author

[havitoporto](https://github.com/havitoporto)

## Acknowledgments

- Flutter team for the web framework
- Contributors and maintainers
