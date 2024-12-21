# Pour Android

```Shell
npx expo prebuild -p android --clean # Le --clean est optionel
cd .\android\
./gradlew ":app:assembleRelease" # Pour une release
./gradlew ":app:assembleDebug" # Pour une app de test
cd app/build/outputs/apk/release # Et là t'as ton apk !
```
