# StoneWork Construction

A premium Flutter app for real-estate + construction workflows.

## Includes
- 15 real screens
- go_router navigation
- Riverpod state management
- Local mock repositories so the app runs before Firebase is connected
- Firebase-ready stubs and Cloud Functions
- Unit, widget, and integration tests
- GitHub Actions CI

## Run
```bash
flutter pub get
flutter run
```

## Firebase later
1. Add `lib/firebase_options.dart`
2. Add native Firebase config files
3. Swap mock repositories in `lib/core/app_state.dart` if desired
4. Deploy `functions/`

## Native folders
This source bundle includes minimal placeholder host folders. To regenerate standard Android/iOS/Web host files with your own Flutter SDK:
```bash
flutter create . --platforms=android,ios,web
```

## Mock mode
The app works locally without Firebase and stores lightweight auth/onboarding state in SharedPreferences.
