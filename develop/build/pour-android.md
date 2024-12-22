# Pour Android
Dans un terminal de commande qui est dans le dossier GitHub Papillon, exécutez ces lignes :
```Shell
npm i
npx expo $prebuild -p android --clean # (--clean optionnel)
cd .\android\
./gradlew ":app:assembleRelease" # Pour une release
./gradlew ":app:assembleDebug" # Pour une app de test
cd app/build/outputs/apk/release # L'APK est disponible ici
```
