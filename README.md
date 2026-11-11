# LiquidGlassLauncher

Android Launcher con:
- Orologio grande e lungo stile iOS (tipo StandBy)
- Effetto Liquid Glass (vetro liquido stile iOS 26)
- Supporto completo come launcher predefinito
- Build automatico APK tramite GitHub Actions

## Come installare (senza computer)

1. Vai nella tab **Actions** di questo repository
2. Clicca sull'ultimo workflow eseguito
3. Scarica l'artifact **app-debug**
4. Estrai lo zip e installa il file `.apk` sul telefono
5. Quando Android ti chiede, scegli **Liquid Glass Launcher** come app home

## Caratteristiche

- Orologio digitale grande e leggibile
- Sfondo con effetto vetro (blur + trasparenza)
- Lista app installate con stile glass
- Pronto per essere impostato come launcher di sistema

## Sviluppo

Tecnologie:
- Kotlin
- Jetpack Compose
- Material 3

### Build locale
```bash
./gradlew assembleDebug
```
