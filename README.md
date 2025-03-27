# Solana Dapp Scaffold

## 🚀 Project Overview

Solana Dapp Scaffold is a mobile application template for building decentralized applications (dApps) on the Solana blockchain. This React Native project provides a robust starting point for developers looking to create mobile blockchain applications with seamless wallet integration and cross-platform support.

### Key Features
- 🔒 Secure Solana wallet connection
- 📱 Cross-platform mobile development (iOS and Android)
- 💸 Blockchain transaction capabilities
- 🌐 Network selection and management
- 🔍 Account balance tracking

## 🌐 Supported Platforms

- **Android**: Full support (version 6.0+)
- **iOS**: Full support (version 13.0+)

### Platform Considerations
- Requires mobile device with internet connectivity
- Recommended minimum RAM: 4GB
- Location services may be required for certain features

## 🛠 Getting Started

### Prerequisites
- Node.js (v16.x or later)
- Yarn or npm
- React Native CLI
- Xcode (for iOS development)
- Android Studio (for Android development)

### Installation Steps

1. Clone the repository:
```bash
git clone https://github.com/yourusername/solanadappscaffold.git
cd solanadappscaffold
```

2. Install dependencies:
```bash
yarn install
# or
npm install
```

3. Install CocoaPods (for iOS):
```bash
cd ios && pod install && cd ..
```

### Environment Configuration

1. Create a `.env` file in the project root for sensitive configurations:
```
SOLANA_NETWORK=mainnet-beta
RPC_ENDPOINT=https://api.mainnet-beta.solana.com
```

## 🚀 Running the App

### iOS
```bash
npx react-native run-ios
# or
yarn ios
```

### Android
```bash
npx react-native run-android
# or
yarn android
```

## 📂 Project Structure

```
solanadappscaffold/
│
├── android/         # Android native project files
├── ios/             # iOS native project files
├── src/
│   ├── components/  # Reusable React components
│   ├── screens/     # App screen implementations
│   ├── providers/   # Context and state management
│   └── App.tsx      # Main application component
│
├── __tests__/       # Unit and integration tests
└── package.json     # Project metadata and dependencies
```

## 🧩 Technologies Used

- **Framework**: React Native 0.70
- **Language**: TypeScript
- **Blockchain**: Solana Web3.js
- **State Management**: React Context
- **Testing**: Jest, React Native Testing Library

## 🖥 Key Screens

1. **Wallet Screen**
   - View account balance
   - Select active network
   - Initiate transactions

2. **Account Management**
   - Connect/disconnect Solana wallet
   - View transaction history

## 🚢 Build and Deployment

### iOS
1. Archive the app in Xcode
2. Upload to App Store Connect via Xcode
3. Submit for review

### Android
1. Generate signed APK:
```bash
cd android && ./gradlew assembleRelease
```
2. Upload to Google Play Console

## 📄 License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

## 🤝 Contributing

Contributions are welcome! Please read our [Contributing Guidelines](CONTRIBUTING.md) before getting started.

## 📞 Support

For issues or questions, please [open an issue](https://github.com/yourusername/solanadappscaffold/issues) on GitHub.