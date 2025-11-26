NavigationApp

A simple React Native application demonstrating bottom-tab navigation, theming (light/dark mode), and basic screens such as Home, Profile, Settings, and more.

 Features

🔹 React Navigation with Bottom Tabs

🔹 Light/Dark Theme Toggle

🔹 Reusable UI components

🔹 Fully responsive layouts

🔹 Android emulator support

🔹 Ready for future API integration

📂 Project Structure
NavigationApp/
│
├── android/
├── ios/
├── src/
│   ├── navigation/
│   │   └── TabNavigator.js
│   ├── screens/
│   │   ├── HomeScreen.js
│   │   ├── ProfileScreen.js
│   │   ├── SettingsScreen.js
│   ├── theme/
│   │   ├── ThemeContext.js
│   │   └── themes.js
│   └── components/
│
└── App.js

🛠️ Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/UICCC/NavigationApp.git
cd NavigationApp

2️⃣ Install dependencies
npm install


or

yarn install

3️⃣ Start Metro Bundler
npm start

📱 Running on Android
Start your emulator manually:
<Your SDK Path>/emulator/emulator.exe @Your_AVD_Name


Then run:

npx react-native run-android


If you see “No devices found”, make sure your emulator is booted.

🎨 Theming (Dark Mode Support)

This project uses a ThemeContext that wraps the entire app.
Dark mode automatically updates UI elements such as:

Background colors

Text colors

Tab bar colors

Status bar appearance

You can toggle dark mode inside Settings Screen.

📸 Screenshots (Add your own)
[ ] Home Screen  
[ ] Dark Mode  
[ ] Settings Screen  
[ ] Profile Screen  

📦 Dependencies

Key libraries:

Library	Purpose
react-navigation	Navigation system
@react-navigation/bottom-tabs	Bottom tab UI
react-native-gesture-handler	Required by navigation
react-native-reanimated	Navigation animations
react-native-vector-icons	Icons
📄 Scripts
Command	Description
npm start	Start Metro
npm run android	Build/run Android app
npm run ios	Build/run iOS app (Mac only)

