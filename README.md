# flutter_finance_app_ui

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

# flutter_finance_app_ui

flutter_finance_app_ui android&#x2F;iOS application.

= = = Android release steps = = =

Generate FAT APK
    - flutter clean
    - flutter build apk --release

Generate split APK's
    - flutter clean
    - flutter build apk --split-per-abi --release 

= = = iOS release steps = = =


Set iOS deployment target

1. Follow below steps
    - setup flutter sdk
    - get packages
    - open runner.xcworkspace from ids folder
    - update version code in yaml

2. Bellow commands will generate the runner.app file
    - flutter clean
    - flutter build ios --release

3. Now open the xcode run/build to check if project has error
    - Select Product -> Archive
    - Follow the uploading steps

= = = How to generate route = = =

flutter pub run build_runner watch --delete-conflicting-outputs
