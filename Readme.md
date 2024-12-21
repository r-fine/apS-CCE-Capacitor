# CropCut Insurance Android App

A WebView-based Android application that wraps the CropCut Insurance web application.

## Description

This application provides a native Android wrapper around the CropCut Insurance web platform, allowing users to access the insurance services through a mobile app interface. The app is built using Ionic and Capacitor framework to provide native capabilities while maintaining the web application's functionality.

## Technical Stack

- Ionic Framework 
- Capacitor 6.2.0
- Android SDK (min SDK 22, target SDK 34)
- Web Technologies (HTML, CSS, JavaScript)

## Features

- Native Android WebView integration
- File system access capabilities

## Setup Requirements

- Node.js and npm
- Android Studio
- JDK 17 or later
- Ionic CLI

## Installation

1. Clone the repository
2. Install dependencies:
```bash
npm install
```
3. Build the web assets:
```bash
ionic build
```
4. Sync with Android project:
```bash
npx cap sync android
```

## Development

To run the app in development:

1. Open the Android project in Android Studio:
```bash
npx cap open android
```
2. Build and run the app on an emulator or device

## Production Build

To create a production build:

1. Build the web assets in production mode:
```bash
ionic build --prod
```
2. Update the Android project:
```bash
npx cap copy android
```
3. Open Android Studio and build the APK/Bundle

## Configuration

The app configuration can be found in:
- `capacitor.config.ts` - Main Capacitor configuration
- `android/app/build.gradle` - Android build settings
- `package.json` - Project dependencies and scripts
