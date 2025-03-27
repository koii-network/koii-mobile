# Solana dApp Scaffold - Mobile Application

## 🚀 Project Overview

This mobile application is a comprehensive Solana blockchain development scaffold, designed to provide developers with a robust starting point for building decentralized mobile applications. The app serves as a template for creating cross-platform mobile dApps with React Native and Solana integration.

### Key Features
- 🔐 Wallet connection and management
- 💱 Balance tracking
- 🌐 Network selection
- 🧩 Modular architecture
- 📱 Cross-platform support (iOS & Android)

## 📱 Supported Platforms

- **Android**: Fully supported (API 21+)
- **iOS**: Fully supported (iOS 13+)

### Platform Compatibility
- React Native version: 0.70.0-rc.4
- Supports both physical devices and simulators/emulators

## 🛠 Getting Started

### Prerequisites
- Node.js (v16+)
- Yarn or npm
- React Native CLI
- Xcode (for iOS development)
- Android Studio (for Android development)

### Installation Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/solana-dapp-scaffold.git
   cd solana-dapp-scaffold
   ```

2. Install dependencies:
   ```bash
   yarn install
   # or
   npm install
   ```

3. For iOS, install pods:
   ```bash
   cd ios
   pod install
   cd ..
   ```

### Environment Setup

1. Create a `.env` file in the project root for any required API keys or configuration:
   ```
   SOLANA_NETWORK=devnet
   # Add other environment variables as needed
   ```

## 🚀 Running the App

### iOS
```bash
npx react-native run-ios
# Or specify a simulator
npx react-native run-ios --simulator="iPhone 14"
```

### Android
```bash
npx react-native run-android
```

## 📂 Project Structure

```
├── android/             # Android native code
├── ios/                 # iOS native code
├── src/
│   ├── components/      # Reusable UI components
│   ├── screens/         # App screen definitions
│   ├── providers/       # Context and state management
│   └── App.tsx          # Main application component
├── __tests__/           # Unit and integration tests
└── index.js             # Entry point
```

## 🧩 Technologies Used

- **Framework**: React Native
- **Language**: TypeScript
- **Blockchain**: Solana Web3.js
- **State Management**: React Context
- **Testing**: Jest, React Native Testing Library

## 🖥 Key Screens and Features

### Wallet Screen
- Connect Solana wallet
- View account balance
- Switch between networks (mainnet, devnet, testnet)

### Network Selection
- Dynamic network switching
- Real-time connection management

## 🚢 Build and Deployment

### iOS
1. Configure app signing in Xcode
2. Build for production:
   ```bash
   npx react-native run-ios --configuration Release
   ```

### Android
1. Generate signed APK:
   ```bash
   cd android
   ./gradlew bundleRelease
   ```

## 📋 Testing

Run tests using:
```bash
yarn test
# or
npm run test
```

## 📄 License

This project is open-source and available under the MIT License. See the [LICENSE](LICENSE) file for more details.

## 🤝 Contributing

Contributions are welcome! Please read the contributing guidelines before getting started.

---

**Made with ❤️ by the Solana Developer Community**