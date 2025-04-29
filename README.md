# Habit Tracker App

A mobile application built with Expo and React Native to help users track and maintain their daily habits.  
The app features a clean, intuitive interface with both light and dark mode support.

## Features
- **Habit Tracking**: Create, manage, and track your daily habits
- **Categories**: Organize habits with different categories (Wajib/Sunah)
- **Explore Section**: Discover new habit ideas and recommendations
- **Dark/Light Mode**: Full support for both light and dark themes
- **Responsive Design**: Works seamlessly across different device sizes

## Tech Stack
- [Expo](https://expo.dev/) - React Native framework
- [Expo Router](https://expo.github.io/router/docs) - File-based routing
- [TypeScript](https://www.typescriptlang.org/) - Type-safe code
- Custom theming system with light/dark mode support

## Getting Started

### Prerequisites
- Node.js (v14 or newer)
- npm or yarn
- Expo CLI

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/habit-tracker.git
2. Navigate to the project directory:
   ```bash
   cd habit-tracker
3. Install dependencies:
   ```bash
   npm install
4. Start the development server:
   ```bash
   npx expo start

## Usage
After starting the development server, you can:

-Open the app on an iOS simulator

-Open the app on an Android emulator

-Scan the QR code with the Expo Go app on your physical device

-Open in a web browser (if web support is enabled)   

## Project Structure
```bash
habit-tracker/
├── app/                  # Main application code with file-based routing
│   └── (tabs)/           # Tab-based navigation screens
├── constants/            # App constants including Colors
├── assets/               # Static assets like images and fonts
└── components/           # Reusable UI components

