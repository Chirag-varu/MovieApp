<div align="center">
  <div>
    <img src="https://img.shields.io/badge/-React_Native-black?style=for-the-badge&logo=react&color=61DAFB" />
    <img src="https://img.shields.io/badge/-Expo-black?style=for-the-badge&logo=expo&color=000020" />
    <img src="https://img.shields.io/badge/-TypeScript-black?style=for-the-badge&logo=typescript&color=3178C6" />
    <img src="https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logo=tailwindcss&color=06B6D4" />
    <img src="https://img.shields.io/badge/-Appwrite-black?style=for-the-badge&logo=appwrite&color=F02E65" />
  </div>

  <h3>🎬 Bollywood Movie Finder App</h3>
  <p>Built using Expo, TypeScript, Tailwind CSS, and Appwrite</p>
</div>

---

## 📽️ About the Project

This is a feature-rich movie browsing app built with React Native and powered by the TMDB API. It’s optimized to help users discover both Bollywood and Indian cinema content, with an enhanced UI and a trending movie algorithm using Appwrite.

---

## ⚙️ Tech Stack

- ✅ **React Native** via Expo
- 🟦 **TypeScript**
- 💅 **Tailwind CSS** (NativeWind)
- 🧠 **Appwrite** for backend services
- 🎞️ **TMDB API** for movie data

---

## 🔥 Features

- 🔍 **Search** for Bollywood & Indian movies
- 🏠 **Home screen** with featured & trending titles
- 📊 **Popularity algorithm** powered by Appwrite
- 🧠 **Real-time data fetching**
- 💡 **Responsive UI** and clean animations

---

## 🚀 Getting Started

### 📦 Prerequisites

- [Node.js](https://nodejs.org)
- [npm](https://npmjs.com)
- [Expo CLI](https://docs.expo.dev/get-started/installation/)
- A TMDB and Appwrite account

### 📁 Clone the Repo

```bash
git clone https://github.com/Chirag-varu/MovieApp.git
cd MovieApp
```

### 🔧 Install Dependencies

```bash
npm install
```

### 🔑 Add Environment Variables

Create a `.env` file in the root:

```env
EXPO_PUBLIC_MOVIE_API_KEY=your_tmdb_key
EXPO_PUBLIC_APPWRITE_PROJECT_ID=your_project_id
EXPO_PUBLIC_APPWRITE_DATABASE_ID=your_database_id
EXPO_PUBLIC_APPWRITE_COLLECTION_ID=your_collection_id
```

### ▶️ Start the App

```bash
npx expo start
```

Scan the QR code using Expo Go on your mobile device.

---

## 📁 Folder Structure

```
.
├── app/
├── components/
├── constants/
├── hooks/
├── interfaces/
├── lib/
├── screens/
└── tailwind.config.js
```

---

## 🧩 Code Snippet - Tailwind Config

```js
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["./app/**/*.{js,ts,jsx,tsx}", "./components/**/*.{js,ts,jsx,tsx}"],
  presets: [require("nativewind/preset")],
  theme: {
    extend: {
      colors: {
        primary: "#030014",
        secondary: "#151312",
        text: "#9CA4AB",
        darkAccent: "#AB8BFF",
        accentText: "#A8B5DB",
      },
    },
  },
};
```

---

## 🧠 Credit

This app is inspired by the tutorial from [JavaScript Mastery](https://www.youtube.com/@javascriptmastery/videos). Big thanks to their team for the detailed breakdown and UI inspiration.

---

## 📸 Screenshots

![WhatsApp Image 2025-04-11 at 11 20 59 AM](https://github.com/user-attachments/assets/7daec73a-7232-4047-8ad7-55a2bc30d37e)
![WhatsApp Image 2025-04-11 at 11 20 59 AM (1)](https://github.com/user-attachments/assets/96f675d4-079b-4a18-a691-9fab58306783)
![WhatsApp Image 2025-04-11 at 11 20 59 AM (2)](https://github.com/user-attachments/assets/56d0f59f-258e-4bc6-8aa9-47c0f6b77336)

---

## 📬 Contact

Built by [**Chirag Varu**](https://github.com/Chirag-varu) 🚀  
Let's connect on [Instagram](https://instagram.com/) or [LinkedIn](https://www.linkedin.com/in/chiragvaru03/)!

---
