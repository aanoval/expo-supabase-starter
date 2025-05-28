# Simple React Native App

A simple React Native application that builds an unsigned APK using GitHub Actions.

## Features

- Simple React Native app with one page
- GitHub Actions workflow for automatic APK building
- No local build required

## GitHub Actions

The `.github/workflows/build-android.yml` workflow will automatically:
1. Build the app when code is pushed to main branch
2. Generate an unsigned APK
3. Upload the APK as a build artifact

## Getting Started

1. Clone the repository
2. Push your changes to the main branch
3. Wait for GitHub Actions to build the APK
4. The APK will be available as a build artifact in the Actions tab
