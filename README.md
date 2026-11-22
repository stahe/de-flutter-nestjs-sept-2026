# Ein Client-Server-Beispiel - Flutter / NestJS (2026)

Dieses Repository gehört zum Kurs **„Ein Client-Server-Beispiel - Flutter / NestJS (2026)“**, veröffentlicht unter:

**https://stahe.github.io/de-flutter-nestjs-sept-2026/**

## Überblick

Dieses Dokument überträgt die Lehranwendung **RdvMedecins** (Terminplanung in einer Arztpraxis) – die bereits in den Kursen zu Angular, React und Vue.js behandelt wurde – auf aktuelle Technologien. Hier wird eine mobile Version vorgestellt: ein **Flutter**-Client (Dart), der auf einem **NestJS**-Server (TypeScript) aufsetzt, der eine durch JWT-Authentifizierung geschützte JSON-API (Rollen ADMIN / USER) bereitstellt.

Das Dokument richtet sich an Leser, die bereits mindestens ein Web-Framework (Angular, React oder Vue.js) kennen und Flutter im Vergleich dazu lernen: Jedes Flutter-Konzept wird mit seinem Pendant in diesen Frameworks verknüpft.

Der Kurs behandelt:

- die Einrichtung der Entwicklungsumgebung (VSCode, Flutter SDK, Android Studio, Android SDK, Vorbereitung eines Android-Smartphones und eines Emulators, `flutter doctor`);
- die Installation und den Start des NestJS-Servers der Anwendung (MySQL-Datenbank, Konfiguration, Tests mit einem Browser und mit Postman);
- eine Einführung in Flutter (Widgets, `StatelessWidget`/`StatefulWidget`, Zustandsverwaltung mit `provider`, die Sprache Dart);
- einen ausführlichen Durchgang durch den Flutter-Client der Anwendung RdvMedecins, Datei für Datei;
- die Portierung desselben Quellcodes auf drei Zielfamilien: mobil (Android/iOS), Desktop (Windows/macOS/Linux) und Web, wobei die mobilspezifischen Herausforderungen (Serveradresse, unverschlüsselter HTTP-Verkehr, schmale Bildschirme) behandelt werden;
- ein Fazit zum Erreichten und Ansatzpunkte für die Weiterentwicklung.

## Autoren

- **Hauptautor:** KI Claude (Anthropic)
- **Prüfer:** Serge Tahé
