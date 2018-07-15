# Android-Jetpack-Test

![Resultat final](https://github.com/eric-ampire/Android-Jetpack-Test/blob/master/Deepin%20Capture-%C3%A9cran_zone%20de%20s%C3%A9lection%20_20180715175825.png)

Pour pouvoir utiliser les composants de la collection Architecture, il faut:

1. Android Studio version 3.2+
2. Inclure toutes les dependances liée a la collection cible

## Exemple

```
dependencies {
    implementation fileTree(dir: 'libs', include: ['*.jar'])
    implementation "org.jetbrains.kotlin:kotlin-stdlib-jdk7:$kotlin_version"
    implementation 'androidx.appcompat:appcompat:1.0.0-alpha1'
    implementation 'androidx.constraintlayout:constraintlayout:1.1.2'
    implementation 'androidx.legacy:legacy-support-v4:1.0.0-alpha1'
    testImplementation 'junit:junit:4.12'
    androidTestImplementation 'androidx.test:runner:1.1.0-alpha3'
    androidTestImplementation 'androidx.test.espresso:espresso-core:3.1.0-alpha3'
    implementation 'android.arch.navigation:navigation-fragment:1.0.0-alpha02'     // cette est obligatoire
}
```


Une fois toutes les librairie en place, vous pouvez maintenant vous mettre au travail en creant le sous dossier navigation dans le dossier res de votre projet, une fois que ce fait crée un fichier xml (navigation.xml dans ce cas) qui contiendra le graph de votre application 


![Resultat final](https://github.com/eric-ampire/Android-Jetpack-Test/blob/master/Deepin%20Capture-%C3%A9cran_sun-awt-X11-XFramePeer_20180715175927.png)

Pour plus d'information [Android Jetpack](https://developer.android.com/jetpack/) !


