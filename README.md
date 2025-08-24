PineCityZoo Visitor App

A comprehensive mobile application designed to enhance the visitor experience at Pine City Zoo by providing interactive features, educational content, and seamless navigation.

📱 About the App

PineCityZoo App is developed as part of the FNB App Academy projects initiative, aimed at modernizing zoo visitor experiences through digital innovation. The app serves as a digital companion for zoo visitors, offering real-time information and interactive services.

✨ Features

Interactive Zoo Map: Real-time navigation with points of interest

Animal Database: Detailed information about species, habitats, and conservation status

Event Calendar: Upcoming events, feeding times, and special shows

Digital Ticketing: Purchase and store tickets within the app

Educational Content: Learning resources and fun facts about wildlife

Notification System: Alerts for events and important updates

Accessibility Features: Support for various visitor needs


🛠️ Technology Stack

Frontend: React Native (iOS & Android compatible)

Backend: Firebase (Authentication, Firestore, Cloud Functions)

Mapping: React Native Maps with custom zoo overlays

State Management: Redux Toolkit

UI Framework: React Native Paper

Payment Integration: Stripe API for ticket purchases


🚀 Installation
Prerequisites
Node.js (v14 or higher)

npm or yarn

React Native development environment setup

iOS: Xcode (for Mac users)

Android: Android Studio

Setup Instructions
Clone the repository:

bash
git clone https://github.com/Neo21702/FNB-App-Academy-projects.git
cd FNB-App-Academy-projects/PineCityZoo
Install dependencies:

bash
npm install
# or
yarn install
Configure environment variables:

bash
cp .env.example .env
# Add your API keys and configuration values
Run the application:

bash
# For iOS
npx react-native run-ios

# For Android
npx react-native run-android

📁 Project Structure

PineCityZoo/
├── src/
│   ├── components/     # Reusable UI components
│   ├── screens/        # App screens
│   ├── navigation/     # Navigation configuration
│   ├── services/       # API services and integrations
│   ├── utils/          # Helper functions and utilities
│   └── store/          # Redux store and slices
├── assets/             # Images, icons, and other media
└── docs/               # Documentation

🔧 Configuration
Obtain API keys for:

Firebase Project

Google Maps (if applicable)

Stripe (for payments)

Update configuration files:

firebase.config.js

app.config.js


🤝 Contributing

This project was developed as part of the FNB App Academy program. While primarily an educational project, we welcome feedback and suggestions.


📄 License

This project is licensed under the MIT License - see the LICENSE file for details.


📞 Support

For questions or support regarding the PineCityZoo app:

Open an issue in this repository

Contact the development team through the FNB App Academy program


🏗️ Future Enhancements

AR animal experiences

Multi-language support

Offline functionality

Social features and photo sharing

Advanced analytics for zoo management
