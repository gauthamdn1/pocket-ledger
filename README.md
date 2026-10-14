# Pocket Ledger

An offline-first Android and iOS expense and savings tracker built with Flutter. The first release keeps records on the device and does not require an account or network connection.

## MVP scope

- Monthly dashboard with income, expenses, balance, and recent activity
- Add income and expenses with date, category, and optional note
- Transaction history with category and month filters; edit and delete
- Savings goals with progress and contributions
- Currency preference (initially INR)
- Local SQLite storage

Savings contributions are stored as dedicated records linked to a goal. They are not counted as expenses, so spending totals stay meaningful.

## Run

Install Flutter (3.24 or newer), then run `flutter pub get` and `flutter run`. Android and iOS are both supported by the shared Flutter app. iOS builds require macOS with Xcode; Android builds require the Android SDK.
