Thank you for your interest!

First thing first, read [DESIGN.md](https://github.com/GetBallot/mobile/blob/master/DESIGN.md) to understand how the project is structured.

## Compiling

### Flutter
Set up [Flutter](https://flutter.io/).

If Android Studio complains that the Dart SDK is not installed, point it to
`~/development/flutter/bin/cache/dart-sdk` (`~/development/flutter` beingfire the directory where you installed Flutter).

### Google Civic Information API
1. Acquire an API key for [Google Civic Information API
](https://developers.google.com/civic-information/docs/using_api).
2. Copy `lib/credentials.dart.template` to `lib/credentials.dart` and put Google API key in it.

### Firebase
1. In [Firebase console](https://console.firebase.google.com/), find the project you created for [Google Civic Information API
](https://developers.google.com/civic-information/docs/using_api).
2. Project Overview &rarr; Add Firebase to your Android app.
3. Put com.getballot as package name
4. Add SHA-1 of `android/debug.keystone`
5. Download `google-services.json`
6. Authentication &rarr; sign-in method &rarr; enable Google

## Issues

Before writing any code, please comment on the corresponding [issue](https://github.com/GetBallot/mobile/issues) to clarify what needs to be done and how you plan to do it. Create an issue if needed.
