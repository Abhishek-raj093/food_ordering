<div align="center">
  <br />
    <a href="https://www.youtube.com/watch?v=LKrX390fJMw" target="_blank">
      <img src="assets/readme/hero.png" alt="Project Banner">
    </a>
  <br />

  <div>
    <img src="https://img.shields.io/badge/-React_Native-black?style=for-the-badge&logoColor=white&logo=react&color=61DAFB" alt="React Native" />
    <img src="https://img.shields.io/badge/-Expo-black?style=for-the-badge&logoColor=white&logo=expo&color=000020" alt="Expo" />
        <img src="https://img.shields.io/badge/-Appwrite-black?style=for-the-badge&logoColor=white&logo=appwrite&color=F02E65" alt="Appwrite" />
    <img src="https://img.shields.io/badge/-Tailwind-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="Tailwind" />
    <img src="https://img.shields.io/badge/-TypeScript-black?style=for-the-badge&logoColor=white&logo=typescript&color=3178C6" alt="TypeScript" />
  </div>

# Fast Food Delivery App

A robust, full-stack Food Delivery mobile application built with React Native, Expo, TypeScript, Tailwind CSS (NativeWind), Zustand, and Appwrite. The application provides a seamless user experience with secure authentication, dynamic search and filtering, cart management, and a modern, responsive UI.

## Features

- **User Authentication:** Secure sign-in and sign-up with email/password.
- **Home Screen:** Highlights featured items and provides quick navigation.
- **Search & Filter:** Explore menu items by category or keyword.
- **Product Details:** View detailed information and images for each menu item.
- **Cart Management:** Add, remove, and customize items in the cart with real-time price updates.
- **Profile Management:** Update user information and preferences.
- **Appwrite Integration:** Utilizes Appwrite for backend, database, and file storage.
- **Modern UI/UX:** Styled with Tailwind CSS using NativeWind for a consistent and responsive design.
- **State Management:** Efficient state handling with Zustand.
- **Error Tracking:** Integrated with Sentry for monitoring and debugging.

## Tech Stack

- **React Native** – Cross-platform mobile development
- **Expo** – Streamlined development and deployment
- **TypeScript** – Type safety and improved developer experience
- **Tailwind CSS (NativeWind)** – Utility-first styling for React Native
- **Zustand** – Lightweight state management
- **Appwrite** – Backend-as-a-service for authentication, database, and storage
- **Sentry** – Application monitoring and error tracking

## Project Structure

```
.
├── app/                # Application screens and layouts
│   ├── (auth)/         # Authentication-related screens
│   ├── (tabs)/         # Main tab screens (home, search, cart, profile)
│   └── globals.css     # Tailwind/NativeWind global styles
├── assets/             # Fonts, icons, and images
├── components/         # Reusable UI components
├── constants/          # Static data and constants
├── lib/                # Appwrite logic, data seeding, and hooks
├── store/              # Zustand stores (auth, cart)
├── type.d.ts           # TypeScript types and interfaces
├── .env                # Environment variables (Appwrite configuration)
├── package.json
└── README.md
```

## Getting Started

### 1. Clone the Repository

```sh
git clone https://github.com/your-organization/food_ordering.git
cd food_ordering
```

### 2. Install Dependencies

```sh
npm install
```

### 3. Configure Environment Variables

Create a `.env` file in the root directory with your Appwrite credentials:

```
EXPO_PUBLIC_APPWRITE_PROJECT_ID=your_project_id
EXPO_PUBLIC_APPWRITE_ENDPOINT=https://your-appwrite-endpoint/v1
```

### 4. Start the Application

```sh
npx expo start
```

Open the app using Expo Go or an emulator.

## Assets

All images, icons, and fonts are located in the `assets/` directory.

## Documentation

- [React Native Documentation](https://reactnative.dev/)
- [Expo Documentation](https://docs.expo.dev/)
- [Appwrite Documentation](https://appwrite.io/docs)
- [NativeWind Documentation](https://www.nativewind.dev/)
- [Zustand Documentation](https://docs.pmnd.rs/zustand/getting-started/introduction)
- [Sentry Documentation](https://docs.sentry.io/platforms/react-native/)

---

**This project is maintained for educational and demonstration purposes.**
