# NFT Application


![App Screenshot](https://user-images.githubusercontent.com/29016489/189307034-6fbaa32f-8312-4b46-820e-3ce823d593bf.png)

## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Technologies Used](#technologies-used)
4. [Setup and Running](#setup-and-running)
   - [Windows](#windows)
   - [macOS](#macos)
   - [Linux](#linux)
   - [iOS](#ios)
   - [Android](#android)
   - [Web](#web)

## Introduction
This project is a cross-platform NFT application UI built using Flutter. It provides a sleek and modern interface for interacting with NFTs.

## Features
- Cross-platform support (Windows, macOS, Linux, iOS, Android, Web)
- Modern UI design
- Easy navigation
- Integration with Google Fonts
- Customizable themes

## Technologies Used
- **Flutter**: Framework for building natively compiled applications.
- **Dart**: Programming language optimized for building mobile, desktop, server, and web applications.
- **CMake**: Build system generator.
- **Google Fonts**: Custom fonts integration.
- **Cupertino Icons**: iOS style icons.
- **dot_navigation_bar**: Navigation bar package.

## Setup and Running

### Windows
1. **Install Dependencies:**
   - [CMake](https://cmake.org/download/)
   - [Visual Studio](https://visualstudio.microsoft.com/)
2. **Build and Run:**
   ```sh
   mkdir build
   cd build
   cmake ..
   cmake --build . --config Release
   .\Release\nftui.exe
   ```

### macOS
1. **Install Dependencies:**
   - [Xcode](https://developer.apple.com/xcode/)
2. **Build and Run:**
   - Open `Runner.xcodeproj` in Xcode.
   - Select the `Runner` target and choose a simulator or a connected device.
   - Click the Run button or press `Cmd + R`.

### Linux
1. **Install Dependencies:**
   - [CMake](https://cmake.org/download/)
   - GTK+3
2. **Build and Run:**
   ```sh
   mkdir build
   cd build
   cmake ..
   cmake --build . --config Release
   ./nftui
   ```

### iOS
1. **Install Dependencies:**
   - [Xcode](https://developer.apple.com/xcode/)
2. **Build and Run:**
   - Open `Runner.xcodeproj` in Xcode.
   - Select the `Runner` target and choose a simulator or a connected device.
   - Click the Run button or press `Cmd + R`.

### Android
1. **Install Dependencies:**
   - [Android Studio](https://developer.android.com/studio)
2. **Build and Run:**
   - Open the project in Android Studio.
   - Click the Run button or press `Shift + F10`.

### Web
1. **Install Dependencies:**
   - [Flutter](https://flutter.dev/docs/get-started/install)
2. **Build and Run:**
   ```sh
   flutter build web
   flutter serve
   ```
