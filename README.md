# Daily Hustle Tracker Android project

## Included setup
- Starting bike odometer: 32,473 km
- Next service target: 33,800 km (1,327 km remaining at setup)
- Starting purse cash: Rs 3,350
- Work start plan: 6:45 PM
- Boarding/rent reminder: Rs 9,000 due on the 11th monthly
- Bike finance reminder: Rs 25,500 due on the 20th monthly
- Meal expenses are separated into breakfast, lunch, dinner, and tea/snacks/drinks.
- Daily/weekly/monthly/yearly reports, income, expenses, purse cash, CSV export and JSON backup.

## Build APK using GitHub on a phone
1. Download and extract this ZIP.
2. Upload the extracted project files and folders to a GitHub repository's `main` branch. Make sure `.github/workflows/build-apk.yml` is included; mobile upload can hide dot-folders, so verify it in the repository.
3. Open the repository in GitHub, tap Actions, select "Build Android APK", then "Run workflow" (or push a commit to main).
4. Wait for the workflow to finish successfully.
5. Open the completed workflow run and download the `daily-hustle-tracker-debug-apk` artifact.
6. Extract the artifact ZIP and install `app-debug.apk`. Android may ask to allow installs from that browser/file manager.

## Notes
This is an offline-first app. Records are stored locally on the device and do not automatically sync to a server or Uber Eats/bank/social platforms. Use Backup data regularly. Clearing app data or uninstalling can erase records.
Monthly bill reminders are displayed when the app is opened; Android notifications while the app is closed need additional native notification setup.
