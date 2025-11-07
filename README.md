# ShopS 🛒

A modern mobile shopping application built with React Native and Expo, designed to provide users with a smooth and intuitive e-commerce experience.

## Overview

ShopSmart is a cross-platform shopping application that allows users to browse products, manage their shopping cart, maintain wishlists, and handle user authentication. The app features a clean, responsive interface with bottom tab navigation for easy access to key features.

## Features

- **User Authentication** - Secure login system for personalized shopping
- **Home Screen** - Browse featured products and recent items
- **Product Catalog** - Explore available products with detailed views
- **Shopping Cart** - Add items and manage purchases
- **Wishlist** - Save favorite products for later
- **User Profile** - Manage account settings and preferences
- **Bottom Tab Navigation** - Quick access to all main features

## Tech Stack

- **Framework**: React Native 0.70.5
- **Platform**: Expo ~47.0.8
- **UI Components**: React Native Elements (RNEUI)
- **Styling**: NativeWind (Tailwind CSS for React Native)
- **Navigation**: React Navigation 6.x
- **Fonts**: Roboto (Google Fonts)
- **Icons**: React Native Vector Icons

## Project Structure

```
ShopS/
├── App.js                 # Main application entry point
├── screens/               # Screen components
│   ├── Login.jsx         # Authentication screen
│   ├── Home.jsx          # Home/landing screen
│   ├── Products.jsx      # Product listing
│   ├── Cart.jsx          # Shopping cart
│   ├── Wishlist.jsx      # Saved items
│   └── User.jsx          # User profile
├── components/            # Reusable components
│   ├── Navbar.jsx        # Navigation bar
│   ├── BottomTabs.jsx    # Bottom navigation
│   ├── Box.jsx           # Container component
│   └── Recent.jsx        # Recent items display
└── assets/               # Images, fonts, and static resources
```

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- Expo CLI
- iOS Simulator (for Mac) or Android Studio (for Android development)

### Installation

1. Clone the repository:

```bash
git clone <repository-url>
cd ShopS
```

2. Install dependencies:

```bash
yarn install
# or
npm install
```

3. Start the development server:

```bash
yarn start
# or
npm start
```

### Running the App

- **iOS**: Press `i` in the terminal or run `yarn ios`
- **Android**: Press `a` in the terminal or run `yarn android`
- **Web**: Press `w` in the terminal or run `yarn web`

Alternatively, scan the QR code with the Expo Go app on your mobile device.

## Development

### Available Scripts

- `yarn start` - Start the Expo development server
- `yarn android` - Run on Android device/emulator
- `yarn ios` - Run on iOS simulator
- `yarn web` - Run in web browser

### Configuration

The app uses:

- **Tailwind CSS** configuration in `tailwind.config.js`
- **Babel** configuration in `babel.config.js`
- **Expo** settings in `app.json`

## Platform Support

- ✅ iOS (iPhone & iPad)
- ✅ Android
- ✅ Web

## Version

Current version: **1.0.0**

## License

## This project is private and proprietary.

Built with ❤️ using React Native and Expo
