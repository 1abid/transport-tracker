# Android App

This is an Android app that resides with each asset to be tracked.
Once configured, this app keeps its location synced with Firebase, and reports
on other metrics, such as battery life.

## Usage

This app has two dependencies: the
[fused location provider](https://developers.google.com/android/reference/com/google/android/gms/location/FusedLocationProviderApi)
in the Google Play services location APIs, 
and [Firebase Realtime Database](https://firebase.google.com/docs/database/).

To authenticate to Firebase, populate the `serviceAccountKey.json` file using the
process outlined in
[Firebase Admin SDK setup](https://firebase.google.com/docs/admin/setup).
