# Trading Analyzer Pro

An AI-powered mobile application that analyzes financial charts using Fibonacci strategies and Support & Resistance (S&R) levels to provide professional trading recommendations.

## Features

- **Image Upload and Analysis**
  - Upload chart images from gallery or capture via camera
  - AI-powered chart analysis with OCR capabilities

- **Technical Analysis Tools**
  - Fibonacci Retracement and Extension levels
  - Support & Resistance detection
  - Trading signals generation

- **Multilingual Support**
  - English and Arabic language support
  - RTL layout support for Arabic

- **User-Friendly Interface**
  - Clean and intuitive design
  - Dark/Light mode support
  - Responsive layout

## Getting Started

### Prerequisites

- Flutter SDK (>=2.19.0)
- Dart SDK (>=2.19.0)
- Android Studio / Xcode
- Firebase account (for backend services)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/trading-analyzer-pro.git
   ```

2. Install dependencies:
   ```bash
   flutter pub get
   ```

3. Configure Firebase:
   - Create a new Firebase project
   - Add Android and iOS apps to your Firebase project
   - Download and add the configuration files:
     - `google-services.json` for Android
     - `GoogleService-Info.plist` for iOS

4. Run the app:
   ```bash
   flutter run
   ```

## Project Structure

```
lib/
├── config/
│   └── theme.dart
├── providers/
│   └── language_provider.dart
├── screens/
│   └── home_screen.dart
├── widgets/
│   ├── chart_analysis_result.dart
│   └── language_selector.dart
└── main.dart
```

## Dependencies

- `provider`: State management
- `image_picker`: Image selection and capture
- `google_mlkit_text_recognition`: OCR capabilities
- `flutter_localizations`: Internationalization
- `firebase_core`: Firebase integration
- `firebase_auth`: Authentication
- `cloud_firestore`: Database
- `firebase_storage`: File storage
- `firebase_messaging`: Push notifications

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

Your Name - [@yourtwitter](https://twitter.com/yourtwitter)

Project Link: [https://github.com/yourusername/trading-analyzer-pro](https://github.com/yourusername/trading-analyzer-pro) 