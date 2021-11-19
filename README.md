# Hello Flutter

## My Dev Space Specs
* Flutter (Channel stable, 2.5.3, on Ubuntu 21.10 5.13.0-21-generic, locale en_IN)
* Android SDK (version 31.0.0)
* Android Studio (version 2020.3)
* VS Code (version 1.62.0)
* Ubuntu (version 21.10)

## Install Flutter in Ubuntu 21.10
1. Install java its needed for Android App dev later stage `sudo apt-get install openjdk-8-jdk` will go with open jdk as other guy is harder to install.
2. Use snap to install flutter `sudo snap install flutter --classic`
3. Next install Android Studio using snap `sudo snap install android-studio --classic`, then configure it.
4. Go to `Preferences > Appearance  Behavior > System Settings > Android SDK > SDK Tools` and install **Android SDK Command-line Tools (latest)**
5. Execute `flutter sdk-path` to let flutter install some dependecies and wait for it to finish.
6. Run `flutter doctor --android-licenses`
7. Finally run `flutter doctor` everything should be checked by now.

## This app
1. Created using `flutter create appname`
2. To run `flutter run`