# Pour Android
Dans un terminal de commande qui est dans le dossier GitHub Papillon, exécutez ces lignes :

{% tabs %} {% tab title="Release" %}

git clone git@github.com:PapillonApp/Papillon.git  
cd Papillon  
npm install  
npx expo prebuild -p android --clean # (--clean optionnel)  
cd .\android\  
./gradlew ":app:assembleRelease"  

{% endtab %}

{% tab title="test" %}
git clone git@github.com:PapillonApp/Papillon.git  
cd Papillon  
npm install  
npx expo prebuild -p android --clean # (--clean optionnel)  
cd .\android\  
./gradlew ":app:assembleDebug"  

{% endtab %} {% endtabs %}

L'APK est disponible ici

```Shell
cd app/build/outputs/apk/release 
```
