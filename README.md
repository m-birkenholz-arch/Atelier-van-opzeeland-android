# Atelier van Opzeeland – Android

Android WebView-app voor https://ateliervanopzeeland.nl/

## Functies
- Website opent als zelfstandige Android-app
- JavaScript, cookies en lokale opslag ondersteund
- Uploadvelden openen de Android-bestandskiezer (ook meerdere bestanden)
- Telefoon-, e-mail-, WhatsApp- en externe links openen in de juiste app/browser
- Android-terugknop navigeert eerst terug binnen de website
- Websitewijzigingen zijn direct zichtbaar zonder een nieuwe APK

## APK bouwen via GitHub
1. Maak een nieuwe GitHub repository.
2. Upload alle bestanden en mappen uit dit project naar de repository-root.
3. Open het tabblad **Actions**.
4. Open **Build Android APK**.
5. Klik **Run workflow** of wacht op de automatische build na upload/push.
6. Na een geslaagde build staat onder **Artifacts**: `Atelier-van-Opzeeland-APK`.
7. Download en pak die ZIP uit. Daarin staat `app-debug.apk`.

Deze debug-APK is direct sideloadbaar op Android. Voor publicatie in Google Play is een release-signingconfiguratie nodig.
