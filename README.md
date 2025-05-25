# Smart Yoga Mat

## Project Overview
The Smart Yoga Mat is a Flutter-based mobile application prototype that connects to and controls a smart yoga mat device via Bluetooth. The app provides features for yoga practice, meditation, and fitness tracking.

## Technologies Used

### Core Technologies
- Flutter/Dart - Cross-platform mobile development framework
- Firebase - Backend services (Auth, Firestore, Storage)
- Provider - State management
- flutter_blue_plus - Bluetooth connectivity
- just_audio - Audio playback for meditation sounds

### UI/UX Libraries
- google_fonts - Custom typography
- animate_do - Smooth animations
- fl_chart - Analytics visualization
- lottie - Advanced animations
- cached_network_image - Image caching

## Architecture

### State Management
- Provider pattern for app-wide state management
- Separate service classes for distinct functionalities:
    - AuthService - User authentication
    - MatConnectionService - Bluetooth connectivity
    - AudioService - Sound management
    - AnalyticsService - Usage tracking
    - UpdateService - Firmware updates

### Key Features

1. Authentication
- Email/password and Google Sign-in
- Secure user profile management
- Password reset functionality

2. Mat Connection
- Bluetooth device scanning
- Real-time connection status
- Battery level monitoring
- Firmware version tracking

3. Mat Controls
- Warm-up mode with temperature control
- Relaxation mode with haptic feedback

4. Audio Features
- Meditation sounds library
- Background audio playback
- Category-based sound organization
- Volume and playback controls

5. Analytics
- Session tracking
- Usage statistics
- Progress visualization
- Feature usage analysis

## Security Measures

1. Firebase Security Rules
- Strict user data access control
- Protected audio and product collections
- Admin-only write permissions for sensitive data

2. Authentication
- Secure token management
- Session handling
- Protected routes



## Getting Started

1. Clone the repository
2. Install dependencies:
```bash
flutter pub get
```

3. Run the app:
```bash
flutter run
```
