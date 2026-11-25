# Radio Long Distance – AM/FM OBN

Cross-platform Expo / React Native starter app for Android and iOS.

## Features
- Afaan Oromoo / English interface toggle
- Search community-listed online radio stations
- FM / AM category filters (directory tags are approximate)
- Play supported internet audio streams
- Save favourite stations locally
- Add your own station with its stream URL, frequency and location
- Dark navy and red OBN-inspired theme

## Important limitation
This app plays internet audio streams. Typing an AM/FM frequency does not make a phone receive distant over-the-air broadcasts. A station must provide a working stream URL. Some directory entries may be unavailable or incompatible. Long-distance reception without internet requires separate receiver hardware and a communications link.

## Run locally
1. Install Node.js LTS and Expo Go on your phone.
2. Extract this project.
3. In this folder run `npm install`.
4. Run `npx expo start` and scan the QR code with Expo Go.

## Build installable apps
Use Expo Application Services (EAS):
- `npm install -g eas-cli`
- `eas login`
- `eas build:configure`
- Android: `eas build --platform android`
- iOS: `eas build --platform ios` (Apple Developer account and Apple signing are required for normal device distribution)

This ZIP is source code, not an APK or an iOS IPA. The app has not yet been published to app stores.

## Radio directory
Station search uses the community Radio Browser API. Results and stream availability are not guaranteed.
